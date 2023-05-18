# It works! ;-)


## Section 1

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras mattis consectetur purus sit amet fermentum. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Sed posuere consectetur est at lobortis.


## Section 2

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Donec ullamcorper nulla non metus auctor fringilla. Cras mattis consectetur purus sit amet fermentum. Donec ullamcorper nulla non metus auctor fringilla. Cras justo odio, dapibus ac facilisis in, egestas eget quam.

Vestibulum id ligula porta felis euismod semper. Maecenas faucibus mollis interdum. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.


[Features](Features.md)





```plantuml
@startuml
folder ART
folder SRC
folder REQ
folder IMG
folder PAR
folder STR
folder RIC
folder REL
folder GES
folder EC2239_CC_rev_XX_YY_ZZ_Boiler

REL "1" *-- "molti" EC2239_CC_rev_XX_YY_ZZ_Boiler : contiene
EC2239_CC_rev_XX_YY_ZZ_Boiler "1" o-- "1" SRC
EC2239_CC_rev_XX_YY_ZZ_Boiler "1" o-- "1" REQ
EC2239_CC_rev_XX_YY_ZZ_Boiler "1" o-- "1" ART
ART "1" o-- "1" IMG
ART "1" o-- "1" STR
ART "1" o-- "1" RIC
ART "1" o-- "1" PAR

note right of SRC
  Sorgenti
end note

note right of REQ
  Requisiti software
end note

note right of IMG
  Immagini
end note

note right of STR
  Testi
end note

note right of PAR
  Parametri
end note

note right of RIC
  Ricette
end note

note right of REL
  Rilasci versioni ufficiali
end note

note right of ART
  Artefatti
end note

@enduml
```
