---
title: Korean Online Site Betting System
description: 
published: true
date: 2022-10-08T03:34:45.052Z
tags: 
editor: markdown
dateCreated: 2022-10-08T03:32:49.764Z
---

> This betting system is exclusively used in Korean online sites and is borrowed from Poker and other showdown game implementations.
{.is-warning}

# Betting

Before the game starts, determine the **pping** [삥], which is the *minimum bet size* a player can make.

## Betting Round
Betting turns start from the dealer and moves counter-clockwise.

During a player's betting turn, they may choose one of the following actions:
|Name|Description|
|:---:|:---|
|**Minimum**</br>(삥, *pping*)|Place the minimum bet amount in the pot.</br>*This can only be done if nobody has bet during that betting round previously.*|
|**Call**</br>(콜, *kol*)|Place the same amount as the previous bet.|
|**Double**</br>(따당, *ttadang*)|Raise the bet to double the amount as the previous bet.|
|**Full**</br>(풀, *pul*)|Raise the bet to the full amount of the pot.</br>*The amount must be higher than the previous bet.*|
|**Half**</br>(하프, *hapeu*)|Raise the bet to half the amount of the pot.</br>*The amount must be higher than the previous bet.*|
|**Quarter**</br>(쿼터, *kweoteo*)|Raise the bet to one-fourth the amount of the pot.</br>*The amount must be higher than the previous bet.*|
|**Check**</br>(체크, *chekeu*)|Wait until the end of the betting round before making a decision.</br>*After the betting round goes back to your turn, you can only either make a bet or fold (Die).*|
|**Die**</br>(다이, *dai*)|Fold; Forfeit the round and lose all the amount you have bet during that round.|

The betting round ends if all players who have not folded have same amount of bets. 

> Some players play such that the betting round loops for only a limited number of times. House rules prevail.
{.is-warning}

Players who have not folded then proceed to *showdown*.

>If all players except one fold, the last remaining player collects the pot without proceeding to *showdown*.
{.is-info}