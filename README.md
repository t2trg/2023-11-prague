# 2023-11-prague
Work meeting at Prague on 2023-11-03, Hackathon at IETF 118

**Time:** Friday, November 3rd, 09:00-17:00 UTC (work meeting)<br>
Saturday, November 4th and Sunday, November 5th (Hackathon)

Location: IETF 118 venue, Room Florenc 1/2 @ Prague Hilton, Prague, CZ

Meetecho:
https://meetings.conf.meetecho.com/interim/?short=6926e324-e1d3-4704-957f-53584db705b3

Local time in various locations:<br>
https://www.timeanddate.com/worldclock/fixedtime.html?msg=T2TRG+work+meeting&iso=20231103T0900&p1=1440&ah=8<br>

We are currently looking at an overall structure of the Friday agenda like this:


| Time      | Subjects                                                                                                                                         |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| 1000–1200 | Welcome; <br>10:30: draft-lee-asdf-digital-twin (KST timezone), <br>Security topics: Raytime; active RG documents                              |
| 1200–1330 | (Lunch break)                                                                                                                                    |
| 1330–1530 | (Security overflow), Secure Discovery & self-description security considerations; more self-description issues<br>Protocols and Specifications |
| 1530–1600 | (Coffee break)                                                                                                                                   |
| 1600–1800 | non-IP Cluster: Intro, NIPC, Onion CoAP, GATT…                                                                                                   |

Specific subjects proposed (not complete, please fill in):

## Security Topics

(Christian Amsüss:) 

* <https://datatracker.ietf.org/doc/draft-amsuess-t2trg-raytime/>

  as a short intro, with the questions of "does this fit here" and
  "where (else) was this already (almost) done"?

(Active documents:)

* <https://datatracker.ietf.org/doc/draft-irtf-t2trg-security-setup-iot-devices/>
* <https://datatracker.ietf.org/doc/draft-irtf-t2trg-taxonomy-manufacturer-anchors/>
* <https://datatracker.ietf.org/doc/draft-irtf-t2trg-amplification-attacks/>

### Secure Discovery, self-description security consideration

(Carsten Bormann:)

* discovery access control,  secure discovery,  privacy-preserving discovery -- Security Objectives and how to get there
  (Continuation of May 2023 discussion)

(Ari Keranen:)

* W3C TD security considerations

## Pivoting over to general self-description topics

### self-descriptions: instance vs. class

이현정 (Hyunjeong Lee): 

https://datatracker.ietf.org/doc/draft-lee-asdf-digital-twin/

(Presentation set at 10:30 to fit Korea timezone.)

### self-descriptions: reading a YANG datastore without fully understanding it

(Laurent Toutain)

## Non-IP Cluster

* Naming and Identity in <https://datatracker.ietf.org/doc/draft-amsuess-core-coap-over-gatt/>


(Eliot Lear:) \[not in first slot]

* OSS for both SCIM and the forthcoming non-IP control (NIPC)

(Christian Amsüss:) 

* <https://datatracker.ietf.org/doc/draft-amsuess-t2trg-onion-coap/>

  with the intention to gather feedback and rally people to actually
  run the experiment

* <https://datatracker.ietf.org/doc/draft-amsuess-core-coap-over-gatt/>
  How does this fit into the non-IP picture
  
* <https://datatracker.ietf.org/doc/draft-bormann-t2trg-slipmux/>
  (as an example of Proximity-based "discovery")
  
