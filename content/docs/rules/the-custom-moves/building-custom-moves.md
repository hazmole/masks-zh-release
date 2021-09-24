---
title: 編寫自訂動作
weight: 2
---

# 編寫自訂動作
動作通常由下列要素組成：
* 一個觸發條件： 「當（某件事）發生時……」
* 一個結果： 「……那麼（其他事情）就會發生。」<br/>
這可能會包括了進行擲骰、或可能就是直接讓某件事發生。
* 風險賭注： 如果這個動作涉及擲骰，那麼就說明在擲出10+、7-9、以及6-時會發生什麼事。

你也必須定義10+、7-9、以及失敗時的結果：10+意味著事情通常會成功；7-9意味著會有一些代價或併發後果；而6-則代表事情通常會變得更糟。

不過除了這些核心要素之外，你還需要確保任何你所編寫的自訂動作都能達成這兩個要求：
* 觸發條件是一個有趣且具有不確定性的行動
* 會導致一個能推動故事發展的結果


## 觸發條件
The key to making good triggers is that the actions themselves need to
be interesting and exciting, and only likely to occur when there’s actual
uncertainty about what will happen. You don’t want triggers based on boring
actions, and you don’t want triggers that come up too often.

Here’s a move with a bad trigger:

<div class='Move'>
當你<b>對成年人說謊時</b>時，擲<b>+優越</b>。

<tag>擲出10+時</tag>，他們會相信你的謊言。<br/>
<tag>擲出7-9時</tag>，只要回答他們的幾個問題，你就會沒事。<br/>
<tag>若失敗</tag>，他們看穿了你……現在你有麻煩了。
</div>

The trigger is so non-specific, the PCs will trigger it all the time, even when
it isn’t all that interesting, even when an adult would absolutely believe their
lies. It’s not evocative on its own, and it won’t lead to interesting fiction as a
result. The trigger would be stronger if it were more focused, like when you
feed false information to the Exemplars.

Here’s a move with a better trigger:

<div class='Move'>
當你<b>對著鏡頭發表聲明</b>時，擲<b>+優越</b>。

<tag>擲出10+時</tag>，選擇三項。<br/>
<tag>擲出7-9時</tag>，選擇二項。

* 你說服了觀眾們以一個你所選擇的標籤屬性來看待你們的團隊
* 你的聲明會為你帶來一個來自觀看者的機會
* 你的聲明將你塑造成了一個成功、且值得關注的英雄；標記一點潛能
* 你的聲明並不會激怒或惹惱任何重要或強大的人物

<tag>若失敗</tag>，你的聲明出了差錯，且聽眾們會以最糟糕的方式解讀你的話語。
</div>

Now, it’s about a specific instance, something that won’t happen all the time.
It says something about your game, too—your game is, in part, about what
your PCs say to the public of the city. And finally, there’s uncertainty attached
to that trigger. We don’t know what happens when one of your PCs makes a
statement to the cameras, and that’s why we have the move.

#### 常見的觸發條件類型
<b>角色行動</b>: 這類動作會在角色採取某個行動時被觸發。
要把動作寫好，請務必把這個行動與某個具體特定的事項掛勾──比如說在某個特定的場所、針對某個特定的角色、使用某個特定的物品，諸如此類。

<div class='Move'>
<b>〈超腦博士的頭盔〉</b><br/>
當你<b>戴上全知頭盔並用心靈感應尋找某人</b>時，擲<b>+古怪</b>。

<tag>若成功</tag>，你得知他確切的位置以及現在正在做的事情。<br/>
<tag>擲出7-9時</tag>，這股心靈聯繫的力量比你預期還要強烈；讓他獲得對你的影響力、或你標記一個狀態，由你決定。

<tag>若失敗</tag>，你找到了對方，但你也同時讓超腦博士注意到了你的位置；做好準備。
</div>


<b>情境</b>: 這類動作會在玩家身處於特定情境時被觸發，通常這會是因為某個NPC或環境採取了行動而導致的。不過，PC仍然必須要處於現場或被捲入其中才能觸發這類動作。

<div class='Move'>
<b>〈獵犬〉</b><br/>
當<b>特工赫許用她的超人類探測器找尋你的下落</b>時，擲<b>+平凡</b>。

<tag>若成功</tag>，如果你現在逃離，你就不會被偵測到。<br>
<tag>擲出10+時</tag>，你搶先特工赫許一步──你可以埋伏她、或者讓她就這麼離開，由你決定。

<tag>若失敗</tag>，她們當場逮到了你。
</div>


<b>從此以後</b>: 這類動作會在你取得它們的時候觸發，且它們的效果會不斷持續作用。它們不需要任何詳實的觸發條件。

<div class='Move'>
<b>〈新典範者〉</b><br/>
（當你取得這個動作且從此之後……）簽署合同並加入典範者團隊。<br>
你獲得在任何時候行使你的權威或公開發言時的持續+1。當你身為他們團隊的一份子時，你永遠無法拒絕典範者們對你的影響力。
</div>


<b>當下處理完畢</b>: 這類動作會在你取得它們的時候被觸發一次。同樣的，它們也不需要任何詳實的觸發條件。

<div class='Move'>
<b>〈重塑〉</b><br/>
（在你取得這個動作之後立刻……）當你進入猛毒幫的其中一個重塑洗腦管時，它將重新編排你的思想和記憶，使你成為武器。按你想要的任意調動你的標籤屬性，只要最後你標籤屬性的總和不變，且危險為+3。GM會告訴你你在這個改造過程中失去了什麼記憶。
</div>

## 效果

Triggers are only one half of a move. You need to know what happens when a
move is triggered, too, and those effects need to be interesting and cool all on
their own. Good effects push the fiction forward and lead to more moves. If a
move doesn’t produce clear new paths after it’s been triggered, then its effects
are weak.

Here’s a move with weak effects:

<div class='Move'>
When you try to pass the threshold of Magus Everard’s Sanctum, roll + Freak. On a
10+, you get in. On a 7-9, you get in, but only if you give Everard Influence over you.
On a miss, you can’t get in.
</div>

None of its possible outcomes are particularly interesting. Getting inside
the Sanctum is interesting, but only because the Sanctum itself is interesting—
this move doesn’t make it any more so. Giving Everard Influence allows for a
Label shift, but devoid of anything else, that’s not very interesting and it’s
detached from the fiction. The miss just plain shuts down the fiction.

Here’s a move with much better effects:

<div class='Move'>
When you hack into Rook Laboratories, roll + Superior. On a 10+,
choose two. On a 7-9, choose one.
• you find information that leaves Rook vulnerable; the GM tells
you how
• you find information that clears up a question of yours; the
GM answers the question
• you find information that fills in a weakness of someone else;
name them, and the GM tells you their vulnerability
• you don’t leave a trace
On a miss, choose one anyway, but you reveal your
intrusion to Rook Security; they know where you are,
and they’re coming...
</div>

In this move, none of the options are explicitly
mechanical—they don’t provide Influence or shift Labels or
anything similar. But they’ll all lead to interesting places
in the story. No matter what information a PC finds, it
opens up new paths for new moves. And if a PC doesn’t
choose “you don’t leave a trace,” the GM has a golden
opportunity to make a move.


#### 常見的效果類型
<b>Direct Effects</b>: Moves can directly affect the fiction, making changes, causing
events, without touching on any mechanical pieces in between.

<div class='Move'>
The Warden : When you slap the Cosmic Warden’s Voidcuffs on someone with
powers, they lose those powers for as long as they are cuffed.
</div>

<b>Label swap</b>: You can create custom moves that change which Labels are used
with which basic moves in particular situations. Always make these Label swap
moves tied to specific situations.

<div class='Move'>
Leech: Powersink saps the metahuman abilities of everyone around him. When you
directly engage Powersink in physical combat, roll + Mundane instead of + Danger.
</div>

<b>Add options</b>: Custom moves can add further options to existing moves,
expanding how they’re useful and making them specific to their surroundings.

<div class='Move'>
Hall of Mirrors: When you assess the situation in the Hall of Eternal Worlds, add
these two questions to the list of options:
• What terrible future for me do I see in one of the mirrors?
• What magnificent future for me do I see in one of the mirrors?
</div>

<b>Inflict a condition</b>: You can always have custom moves inflict conditions on
PCs. Those moves indicate ways that the PCs’ emotions can be affected and
changed, whether they like it or not.

<div class='Move'>
Emotion Vampire: When you reject Solace’s Influence, mark a condition of his
choice in addition to any other results of the move.
</div>

<b>Take or give Influence/shift Labels</b>: You can use custom moves to affect
Influence and Label shifting. The two are intimately tied together, but a move
that takes Influence sets up for later Label shifts, while a move that directly
shifts Labels is immediate and powerful.

<div class='Move'>
Just a Child: The Cuckoo possesses and empowers the bodies of children; it makes
the body diamond-hard, yet it still appears as a child. When you directly engage the
Cuckoo, it takes Influence over you unless you have seen its true form.
</div>

<b>Choose options</b>: You can set up custom moves that allow players to pick
options from a list. The list provides some clear courses for the fiction to follow,
without defining exactly which path it will go down. Make sure that all the
choices on the list are juicy and interesting, each one leading to new possible
moves.

<div class='Move'>
Paper Men: When you take on an army of Carceri drone soldiers, roll + Danger. On
a hit, you win, but barely: you must mark three conditions, and the collateral damage
is expansive. On a 10+, choose two. On a 7-9, choose one.
• you escape the fight with only a few scratches and some trauma; mark one
condition instead of three
• you win the fight definitively and seize Carceri prisoners, weapons, and
equipment
• you minimize the collateral damage to the city and those around you
On a miss, you lose the fight and wake up on a Carceri prison ship. Good luck.
</div>

You can play a few tricks with lists of options, too, including setting up
negative lists where players choose which of a set of bad options they want
to avoid.

<div class='Move'>
Gaze of the Abyss: When the demon creature Gehenna invades your mind, roll +
Superior. On a 10+, choose one. On a 7-9, choose two. On a miss, all three.
• tell Gehenna the person you care about the most in the whole world
• tell Gehenna the one thing you want above anything else
• tell Gehenna the danger you fear the most
</div>

<b>Hold and spend</b>: These kinds of moves are pretty much the same as setting
up a list. The difference is that hold allows players to make their choices later,
after they’ve rolled for the original move, instead of right then and there.

<div class='Move'>
Plug ’n’ Play: When you take a dose of Stormbolt Six, roll + Danger. On a 10+, hold
three. On a 7-9, hold two. On a miss, hold one. Spend your hold 1 for 1 to:
• emit an EMP pulse; take out any electronics in your area
• charge your fists with lightning; inflict an additional condition when you directly
engage
• teleport to any location in sight by riding a lightning bolt there
• stun anyone in your vicinity with a thunderclap
When all your hold is spent, mark a condition and take a powerful blow as the
Stormcloud Six works its way through your system.
</div>