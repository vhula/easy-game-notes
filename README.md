# Easy Game (Poker Notes)

## Table of contents

  * [The Reasons for Betting](#the-reasons-for-betting)
  * [Preflop Hand Ranges and Postflop equities](#preflop-hand-ranges-and-postflop-equities)
  * [Aggression and the Turn](#aggression-and-the-turn)
  * [Bet Sizing and Thin Value](#bet-sizing-and-thin-value)
  * [Player Identification and Basic Handreading](#player-identification-and-basic-handreading)
  * [Isolation theory](#isolation-theory)
  * [Table Dynamics](#table-dynamics)
  * [Creative Preflop Raise Sizes](#creative-preflop-raise-sizes)
  * [Value Streets and Pot Management](#value-streets-and-pot-management)
  * [Showdown Theory](#showdown-theory)
  * [Monotone Boards and Equity](#monotone-boards-and-equity)

## The Reasons for Betting

#### *Each time you're betting - ask yourself: WHY BET?*

There are only two major reasons for betting (and one more):

1. *Value* - betting to get called (or raised) by a worse hand.
2. *Bluff* - betting to get a better hand to fold.
3. *Capitalization of Dead Money (DM)* - making the opponent to fold, whether
his hand better or worse, and collecting money in the pot.

    * Make him fold his equity share in the pot (exception: if the villian is
    likely to bluff AND our hand is strong enough to call a potential bluff).
 
    * The Dead Money more than compensates for the times we are called and lose.

## Preflop Hand Ranges and Postflop equities

#### *Preflop is not vacuum. Think about equity of a hand before raising preflop.*

Most players lose money-without-showdown. They don't play a well-formulated
preflop game that is cohesive with their overall postflop strategy. There is a 
gap between their preflop and postflop plan. They aren't thinking about equity.

> <details>
>  <summary>Example: <b>K8o</b> on Button</summary>
> <p>
> <i>Preflop</i> - Hero raises. BB calls.
> 
> <i>Flop</i>: <b>9:spades:7:diamonds:3:clubs:</b> - BB checks, Hero bets, BB calls
> 
> <i>Turn</i>: <b>2:spades:</b> - BB checks again.
> 
> <b>Now it's complicated.</b>
> If we check - we'll inevitably go to showdown with a weak hand and we'll lose
> a decent pot. Or we could bet, but the turn card isn't scary and he's unlikely
> to fold anything he called on the flop with.
> 
> The real problem with the postflop spot starts all the way back preflop. We
> choose a hand with poor postflop equity and thus we walk into unprofitable
> spots - situations where there is simply nothing we can do right.
> 
> </p>
> </details>

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

1. It's unlikely that the opponent holds a strong hand. 

> <details>
>   <summary>E.g. hero holds <b>A:clubs:5:clubs:</b> on <b>8:clubs:7:clubs:4:hearts:</b>.</summary>
> <p>
> <i>Flop</i>: <b>8:clubs:7:clubs:4:hearts:</b> - Hero bets, opponent calls.
> 
> He usually does not have a powerful hand (<b>88, 77, 44, 65, 87</b>) as he would
> raise these hands.
> Most of his calling range probably includes hands like <b>T9</b>, <b>J9</b>, 
> and <b>A5</b> for
> straight-draws; hands like <b>Q:clubs:T:clubs:</b> or <b>K:clubs:T:clubs:</b>
> for flush-draws, and hands like <b>AJ</b> or <b>KQ</b> that called simply with
> the intention of taking the pot away on the turn. 
> 
> He holds: <i>straight-draws</i>, <i>flush-draws</i>, <i>pair+draws</i>,
> <i>weak pairs</i>, and <i>air</i>.
> 
> </p>
> </details>

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

If our opponent calls on a wet board, his range generally doesn't include monster
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

Most people make decision whether or not to call, raise, or fold based on two
main considerations:

1. **Their cards.** Most players won't fold <b>AA</b> on a <b>JT9</b> board when
facing a ton of action because they've got aces - even though they are
relatively unlikely to be ahead.
2. **The board texture.** <b>QQ</b> is likely to get in a lot of money as an
overpair, but shuts down as soon as an <b>A</b> or a <b>K</b> falls.

The size of the bet facing them, in most scenarios, is distant, distant third.

When we're trying to get value bet bigger. We need to choose a bet size that
makes us sure he is still likely to call with worse. This concept is called
thin value.

**Thin Value Betting** means making a bet to be called by worse hands,
accepting that many better hands will also call the bet and understanding that
the value obtained from worse hands will be more than the money lost to better
hands. The "thinner" you bet the smaller your bet size should generally be.

> <details>
> <summary>Example of Thin Value: Board is <b>T54J5</b></summary>
> <p>
> In all these situations we may bet for value because it's likely that we have
> the best hand.
> 
> <i>We hold <b>JJ</b></i> - It's very easy to bet for value.
> 
> <i>We hold <b>AT</b></i> - Some hands that are likely to call our bet are better
> (<b>AJ, KJ, QJ,</b> etc) and some are worse (<b>KT, QT, T9, T8</b>). The bet for
> value should be around 1/2 of pot.
> 
> <i>We hold <b>T9</b></i> - There are very few hands that are worse that could
> potentially call a bet (<b>T8, 99, 88</b>). The bet for value ought to be very small,
> e.g. 1/5 of pot.
> 
> We need to choose a bet size that makes us sure he is still likely to call with
> worse.
> 
> </p>
> </details>

Value betting is the way to beat poker.  The more value we can squeeze out of
hands that are likely ahead, the more money we’re going to make in the long run.
Understanding how to change your value bet sizes depending on the “thinness” of
your bet will help you get the maximum amount of value with your entire range

## Player Identification and Basic Handreading

Player Identification - **Aggressive** or **Passive**:

1. *Stack size*. If someone's sitting with less than a full buy-in at a table,
and they're not a pro-shortstacker, they're usually **passive**.
2. *Limping*. If someone calls a big blind preflop and doesn't open with a
raise, they're **passive**. This usually applies both to preflop and postflop.
3. *Minraising*. This is generally an indicator of a **passive** player who
finally has something worth playing - especially when he minraises postflop.
Additionally, a lot of players will minraise a wide range preflop and then
play passively postflop.
4. *Number of tables*. If someone is sitting at 6 tables with a full stack on
every single one, they're probably **aggressive**. If somebody is sitting at
only one or two tables, and they have limped, minraised, or not kept a full
stack they're usually **passive**.
5. *3-betting*. If somebody sitting on the left has 3-bet you often and
consistently, they're usually **aggressive**. If somebody has 3-bet you only
once or twice, and especially if they've made the 3-bet unusually small or
unusually large, they're usually **passive**.

<details>
<summary>Player Identification Table</summary>
<p>
<table>
 <tr>
  <th></th>
  <th>Yes</th>
  <th>No</th>
 </tr>
 <tr>
  <th>Stack Size Full</th>
  <td>Aggressive</td>
  <td>Passive</td>
 </tr>
 <tr>
  <th>Limping</th>
  <td>Passive</td>
  <td>Aggressive</td>
 </tr>
 <tr>
  <th>Minraising</th>
  <td>Passive</td>
  <td>Aggressive</td>
 </tr>
 <tr>
  <th>Many Tables</th>
  <td>Aggressive</td>
  <td>Passive</td>
 </tr>
 <tr>
  <th>3-betting</th>
  <td>Aggressive</td>
  <td>Passive</td>
 </tr>
</table>
</p>
</details>


There are only three types of players:

1) *Passive-bad*. This type of player calls all the time and only raises with
an extremelly strong hand. Value bet them all the time and fold to a raise.
2) *Aggressive-bad*. This type of player still calls all the time, but they
sometimes make raises or bets that are inconsistent with any kind of strong
holding. A great example is the flop donk-bet.
3) *Aggressive-good*. This player plays aggressively, bluffing and value betting
in appropriate spots. They balance their ranges and pose a lot of problems both
preflop and postflop for their opponents.

Both *passive-bad* and *aggressive-bad* tend to make big calls, and thus
bluffing them is, in general, a bad strategy.

**The plan for each type of bad
player is simple - against a *passive-bad* player, we value bet them and we
don't make big calls. Against an *aggressive-bad* player, we value bet them and
we do make big calls.**

## Isolation theory

**Isolation**: To raise preflop in order to play a pot with particular player
or players.

Isolation is predicted on three advantages:

1) Card Advantage;
2) Positional Advantage;
3) Skill Advantage.

<b>
Playing a pot in position against a bad player is worth the risk of playing
OOP with K4s hand, while playing a pot in position with J7s against a bunch of
really good players isn't worth very much at all.
</b>

<b>
We need to be constantly thinking of who we’re intending to play pots against.
</b>

## Table Dynamics

Factors that determine table dynamics:

1) Player types. We need to play tighter or looser depending on opponents on
the left or right. For example, if there is whether an aggresive player or a
shortstacker on the left then we need to play tighter; a big fish on the right -
we play looser.
2) Stack sizes. If there are many shorter stacked players hands like **33** and
**67s** go down in value, as they lose implied odds. On the other side, hands
like **KJ** and **AT** increase in value because they loose reverse implied
odds.
3) Positions. Having a good regular on the left and a fish on the right is
very different than having a good regular on the right and a fish on the left.

*Overall strategy*:
**We want to do whatever we can to keep the fish in the pot.**

Example: <i>Fish limps, a good regular raises on the button. We have <b>QJs</b>
on the blinds. It will be a better decision to call a raise and let the fish to
call also. 3-betting in this case will force a fish to fold and we will be
heads-up with a good regular OOP.</i>

## Creative Preflop Raise Sizes

We can raise to one of three sizes:

1) Pot. It's large enough that it gets money in the pot, creating dead money
for profitable c-bets and putting stacks in play more easily. However, if our
opponents are 3-betting us a lot their strategy will be successful if we are
giving to much dead money. So, **by reducing our preflop raise size we 
effectively hamper a light 3-bettor's strategy**. **We should reduce our raise
size if there are good players playing back at us to collect dead money.**
2) Less than pot. Shortstacks and good players are two good reasons to reduce
your raise sizes.
3) More than pot. Sometimes, it will be profitable to raise more than a pot
against weak players who may play fit-or-fold postflop.

*Changing raise sizes will not give away information about your hand if it's
based only on information available to the table(not your cards) - which types
of players are sitting in which seats with what stack sizes. This information is
public.*

Raise sizes are based on three factors:

1) **Skill advantage**. We raise larger when we are better than our opponents.
2) **Positional advantage**. We generally prefer to raise smaller when we are in
position.
3) **Stack size**. The shorter the stack size, the smaller we raise and vice
versa.

*We cannot use card advantage as a reason for raise size preflop*

## Value Streets and Pot Management

Anytime we have a hand, there is a desired amount of value that we are trying
to achieve. In any given spot we're trying to obtain between 0 and 3+ streets
of value. This desired value may change from street to street. As a result,
there are two different types of value:

1) *Static Value*: This refers to the amount of value that we want on any given
action. Thus, preflop with AA, we want 3+ streets of value. If we have **A2**
on an **AQJ** board, we may decide we want 1 street of value on the flop, and
then decide again that we want no more value on a **4** turn and a **9** river.
2) *Dynamic Value*: This refers to the way that desired value changes
throughout the course of a hand. **The ability to reevalueate value is what
separates good players from bad players and prevents us from becoming "married"
to a weak hand.**

*Learning how desired value changes during each street in a hand is a difficult
skill.*

## Showdown Theory

When we can't plausibly justify a bet for either reason #1 or reason #2, it's
usually best to check.

**When should I check behind?**

1) You're unlikely to get called by a worse hand (or make a better hand to fold).
2) You're unlikely to be outdrawn.

**When should I bet?**

1) You're likely to get called by a worse hand (you're still unlikely to make a
better hand fold).
2) You're likely to be outdrawn.

Examples:

> <details>
> <summary><b>KK</b> on <b>A22r</b> flop</summary>
> <p>
> <table>
>  <tr>
>   <th></th>
>   <th>Hero: KK</th>
>   <th>BB: ??</th>
>  </tr>
>  <tr>
>   <th>Preflop</th>
>   <td>Raise</td>
>   <td>Call</td>
>  </tr>
>  <tr>
>   <th>Flop</th>
>   <td>Check</td>
>   <td><b>Check</b></td>
>  </tr>
> </table>
> 
> We can assume here that the big blind will never fold an Ace to a bet; and
> second, that the big blind will never call with a hand worse than an Ace.
> 
> If we bet here and get called, we'll isolate ourselves with hands that beat
> us. If we check, we continut to play against a wider range - and a range
> that we're ahead of. This concept is called <b>range manipulation</b>.
> </p>
> </details>

Understanding when to check behind and when to bet is the essence of showdown
theory.

> <details>
> <summary><b>8:hearts:8:diamonds:</b> on <b>9:clubs:7:clubs:3:spades:</b> flop</summary>
> <p>
> <table>
>  <tr>
>   <th></th>
>   <th>Hero: 88</th>
>   <th>BB: ??</th>
>  </tr>
>  <tr>
>   <th>Preflop</th>
>   <td>Raise</td>
>   <td>Call</td>
>  </tr>
>  <tr>
>   <th>Flop</th>
>   <td>Check</td>
>   <td><b>Bet</b></td>
>  </tr>
> </table>
> 
> While our hand is very likely to be best, we're extremelly likely to be
> outdrawn. This should incline us to bet. Also, we're confident to be called
> by worse hands, including smaller pairs and draws.
> </p>
> </details>

What if we have <b>9:diamonds:9:hearts:</b> on an <b>A:clubs:8:clubs:8:spades:</b>
board? We're very likely to be outdrawn and we're unlikely to be called by a 
worse hand. The ability to weigh these inclinations are what make somebody good
at poker - it's why <b>KK</b> is a bet on an <b>A:spades:Q:spades:9:clubs:</b>
board but a check on an <b>A:clubs:3:hearts:2:spades:</b>.

## Monotone Boards and Equity

Monotone boards are a tricky one. On the one hand, our opponents will have a lot
of pair+draw hands that will call our value bets. On the other hand, all those
hands have a lot of equity in general, so our value bets are inherently thinner.

<i>A raise on a monotone board usually means an extremelly strong hand.</i>

1) People don't call raises preflop with offsuit cards. On a
<b>K:hearts:9:hearts:8:hearts:</b>, most decent players aren't raising their
one-heart hand because they simply don't hold any.
2) On a monotone board, the preflop raiser is likely to have a lot of equity.
With black ace on a <b>K:hearts:9:hearts:8:hearts:</b>, we have decent equity.
With <b>A:hearts:Q:spades:</b>, we have good equity. For this reason, people
don't bluff boards like these - they're way to likely to have smashed the
preflop raiser equity-wise.

<i>Basically, we can expect somebody raising on a monotone board to have an
extremely strong hand.</i>

<i>Monotone boards are good places to make tough folds. They’re not, though,
good places to make bluffs, because most players won’t be as good as we are at
making those tough folds. Just count on our opponents making the mistake of
calling too often and value bet them. </i>