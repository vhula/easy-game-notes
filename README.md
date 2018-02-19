# Easy Game (Poker Notes)

## Table of contents

  * [The Reasons for Betting](#the-reasons-for-betting)
  * [Preflop Hand Ranges and Postflop equities](#preflop-hand-ranges-and-postflop-equities)
  * [Aggression and the Turn](#aggression-and-the-turn)
  * [Bet Sizing and Thin Value](#bet-sizing-and-thin-value)

## The Reasons for Betting

#### *Each time you're betting - ask yourself: WHY BET?*

There are only two major reasons for betting (and one more):

1. *Value* - betting to get called (or raised) by a worse hand.
2. *Bluff* - betting to get a better hand to fold.
3. *Capitalization of Dead Money (DM)* - making the opponent to fold, whether
his hand better or worse, and collecting money in the pot.

    * Make him fold his equity share in the pot (exception: if the villian is
    likely to bluff AND our hand is string enough to call a potential bluff).
 
    * The Dead Money more than compensate for the times we are called and lose.

## Preflop Hand Ranges and Postflop equities

#### *Preflop is not vacuum. Think about equity of a hand before raising preflop.*

Most players lose money-without-showdown. They don't play a well-formulated
preflop game that is cohesive with their overall postflop strategy. There is a 
gap between their preflop and postflop plan. They aren't thinking about equity.

<details>
 <summary>Example: <i>K8o</i> on Button</summary>
<p>
<i>Preflop</i> - Hero raises. BB calls.

<i>Flop</i>: <b>9:spades:7:diamonds:3:clubs:</b> - BB checks, Hero bets, BB calls

<i>Turn</i>: <b>2:spades:</b> - BB checks again.

<b>Now it's complicated.</b>
If we check - we'll inevitably go to showdown with a weak hand and we'll lose
a decent pot. Or we could bet, but the turn card isn't scary and he's unlikely
to fold anything he called on the flop with.

The real problem with the postflop spot starts all the way back preflop. We
choose a hand with poor postflop equity and thus we walk into unprofitable
spots - situations where there is simply nothing we can do right.

</p>
</details>

#### **Choose hands that have good postflop equity.**

1. Suited cards: `A2s+`, usually `A2s-A5s` better than `A6s-A9s`.
2. High cards. With a top pair we usually have the best hand. If we miss we
usually have six outs.
3. Connecting cards: `57s`, `67s`.

## Aggression and the Turn

#### *The combination of pot equity and fold equity is mandatory for us to stay aggressive on the turn.*

```
Pot Equity + Fold Equity = Aggression
```

Sometimes pot equity is so high that fold equity isn't important, e.g.:
<b>Q:hearts:J:hearts:</b> on <b>T:hearts:9:hearts:2:clubs:4:diamonds:</b>

The draw is so strong that we need our opponent to fold a very low persentage of
time for a 2nd barrel to be profitable. On the other hand <b>22</b> on
<b>843Ar</b> lacks of pot equity but is compensated by the fact that the
opponent folds high persentage of the time.

If we have <b>A:spades:5:spades:</b> on
<b>9:spades:7:diamonds:3:clubs:T:spades:</b>:
pot equity is good, but the turn card decreases our fold equity, as it hits
the opponent's range.

#### *Continue aggression if the pot equity and fold equity combination is sufficient*

Sometimes it's better to check-raise instead of betting.

1. It's unlikely that the opponent folds a strong hand. 

<details>
  <summary>E.g. hero holds <b>A:clubs:5:clubs:</b> on <b>8:clubs:7:clubs:4:hearts:</b>.</summary>
<p>
<i>Flop</i>: <b>8:clubs:7:clubs:4:hearts:</b> - Hero bets, opponent calls.

He usually does not have a powerful hand (<b>88, 77, 44, 65, 87</b>) as he would
raise these hands.
Most of his calling range probably includes hands like <b>T9</b>, <b>J9</b>, 
and <b>A5</b> for
straight-draws; hands like <b>Q:clubs:T:clubs:</b> or <b>K:clubs:T:clubs:</b>
for flush-draws, and hands like <b>AJ</b> or <b>KQ</b> that called simply with
the intention of taking the pot away on the turn. 

He holds: <i>straight-draws</i>, <i>flush-draws</i>, <i>pair+draws</i>,
<i>weak pairs</i>, and <i>air</i>.

</p>
</details>

2. It's likely that our opponent will bet a wide weak range on the turn. With his
<i>straight-draws</i>, <i>flush-draws</i>, and <i>air</i> he's going to bet the
vast majority of the time. He's likely to check <i>weak pairs</i> and
<i>pair+draws</i> hands behind, as he'll probably wants to get to showdown.

Therefore, if he bets the turn, the vast majority of his range is very weak, and
now the pot is very large. So, this becomes a good time for us to check-raise
the turn as a semibluff, and of course, for reason #3, capitalization of dead
money.

To compensate for tricky moves of our opponent(call with hands like <b>65</b>,
etc)
we need to make sure we have some equity before making this move. Thus,
<b>A:clubs:5:clubs:</b> on board <b>8:clubs:7:clubs:5:hearts:2:diamonds:</b>
is perfect, as we have a ton of equity. <b>A:clubs:J:clubs:</b> would be fine as
well. <b>K:diamonds:Q:hearts:</b> probably wouldn't be a good idea.

#### *Board texture is critical in understanding when to bet and when to check-raise*

If our opponent calls on a wet board, his range generally doesn't include moster
hands like <i>sets</i>, <i>two pairs</i>, and <i>straights</i>. However, if our
opponent calls on a dry board (<b>864r</b>) check-raising the turn gets
significantly
worse. With fewer draws available, a large portion of his turn-betting range now
includes slow-played <i>sets</i>, <i>two pairs</i>, <i>straights</i>

With <b>A:clubs:5:clubs:</b> on <b>8:clubs:6:diamonds:2:hearts:2:clubs:</b>, I'd
almost certainly bet the turn again and plan on folding to a raise as opposed to
check-raising.

#### *What factors affect our fold equity*

1. **Player type.** This is by far the most significant factor in evaluating
the fold equity. Against a bad player our fold equity is greatly reduced.
2. **Board texture.** Overcards increase fold equity, but low cards and 
coordinating cards don’t.
3. **Number of players.** More players - lower fold equity.
4. **Image and Perceived Hand Range.** Tight, solid history - higher; loose,
bluffy history - lower fold equity.

Sometimes these reasons play against each other.

## Bet Sizing and Thin Value

Most people make decision whether or not to call, raise, or fold baised on two
main considerations:

1. **Their cards.** Most players won't fold <b>AA</b> on a <b>JT9</b> board when
facing a ton of action because they've got aces.
2. **The board texture.** <b>QQ</b> is likely to get in a lot of money as an
overpair, but shuts down as soon as an <b>A</b> or a <b>K</b> falls.

The size of the bet facing them, in most scenarios, is distant, distant third.

