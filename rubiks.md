---
layout: default
title: Rubiks Kub
permalink: rubiks
---
# Lösning

## Notation

| ![](/Img/F.png) | ![](/Img/B.png) | ![](/Img/U.png) | ![](/Img/D.png) | ![](/Img/L.png) | ![](/Img/R.png) |
| F = Front       | B = Back        | U = Up          | D = Down        | L = Left        | R = Right       |
| ![](/Img/Fc.png) | ![](/Img/Bc.png) | ![](/Img/Uc.png) | ![](/Img/Dc.png) | ![](/Img/Lc.png) | ![](/Img/Rc.png) |
| F' = F motsols   | B' = B motsols   | U' = Up motsols  | D' = D motsols   | L' = L  motsols  | R' = R motsols   |
| ![](/Img/F2.png) | ![](/Img/B2.png) | ![](/Img/U2.png) | ![](/Img/D2.png) | ![](/Img/L2.png) | ![](/Img/R2.png) |
| F2 = F halvt varv   | B2 = B halvt varv | U2 = Up halvt varv  | D2 = D halvt varv | L2 = L halvt varv  | R2 = R halvt varv|

## Steg 1 -  Korset

| ![](/Img/Cross.png) | Sätt fyra kanter på rätt plats så det skapar ett kors på en sida. Viktigt att kanternas båda färger stämmer överens med de två mittbitarna de sitter mellan. Vänd kuben upp och ner så korset hamnar på undersidan när det är löst. |

## Steg 2 - Hörnen i första lagret

| ![](/Img/fl.png) | Sätt fyra hörn på rätt plats genom att flytta ner dem från kubens översta lager en och en till kubens understa lager med dessa tre algoritmer. Korset från första steget finns nu på undersidan av kuben och de fyra hörnen med samma färg som korset har är det som ska sättas på rätt plats.  |

| ![](/Img/RURc.png) | ![](/Img/FcUcF.png) | ![](/Img/RU2RcUcRURc.png) |
|     R U R'        | F' U' F              | R U2 R' U' R U R' |

## Steg 3 - Kanterna i andra lagret

| ![](/Img/F2L.png) | Sätt de fyra kanterna som ska sitta i andra lagret rätt med en av dessa algoritmer. |

| ![](/Img/RcUcRcUcRcURUR.png) | ![](/Img/RURURUcRcUcRc.png) | 
|  R' U' R' U' R' U R U R   | R U R U R U' R' U' R' |

## Steg 4 - Vänd kanterna i sista lagret

| ![](/Img/EOLL.png) | Vänd kantbitarna i sista lagret med en av dessa två algoritmer. Om ingen kantbit är rättvänd i sista lagret gör en av de två algoritmerna och sedan en av dem en gång till. |

| ![](/Img/FURUcRcFc.png) | ![](/Img/FRURcUcFc.png) | 
|  F U R U' R' F'              | F R U R' U' F' |

## Steg 5 - Vänd hörnen i sista lagret

| ![](/Img/COLL.png) | Vänd hörnen i sista lagret med denna algoritm. Sätt det hörn som är rättvänt nere till vänster. Upprepa tills alla fyra hörn är rättvända. |

| ![](/Img/RURcURU2Rc.png) |
| R U R' U R U2 R'   |

| ![](/Img/COLL2E.png) | Om två av hörnen är rättvända se till så ett av de felvända hörnen har etiketten som har samma färg som ovansidan sitter i framkanten i nedre vänstra hörnet och gör algoritmen för att få tre felvända hörn. |
| ![](/Img/COLL0E.png) | Om inga av hörnen är rättvända se till så ett av de felvända hörnen har etiketten som har samma färg som ovansidan sitter till vänster i nedre vänstra hörnet och gör algoritmen för att få tre felvända hörn. |

## Steg 6 - Placera hörnen rätt i sista lagret

| ![](/Img/CPLL.png) | Använd algoritmen som cirkulerar tre hörn så alla fyra hörn blir rätt. Den behöver aldrig göras mer än två gånger om man gör rätt. |

| ![](/Img/RcFRcB2RFcRcB2R2.png) |
| R' F R' B2 R F' R' B2 R2|

## Steg 7 - Placera kanterna rätt i sista lagret

| ![](/Img/EPLL.png) | Använd algoritmen som cirkulerar tre kanter så alla föra kanter blir rätt. Snurra översta lagret så en kant som är rätt är längs bort från dig. Om ingen kant sitter rätt gör algoritmen en gång så en kant blir rätt. Gör sedan samma algoritm en gång till.  |

| ![](/Img/RUcRURURUcRcUcR2.png) |
| R U' R U R U R U' R' U' R2 |
