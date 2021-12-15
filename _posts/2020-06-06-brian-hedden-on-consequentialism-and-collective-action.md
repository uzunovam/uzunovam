---
layout: post
title: "Brian Hedden on consequentialism and collective action"
date: 2020-06-06
---
<p>Brian Hedden (2020). <a href="https://doi.org/10.1086/708535" target="_blank" rel="noopener">Consequentialism and collective action</a>. <cite>Ethics</cite> 130 (4): 530–554.</p>

<p>Collective action problems are commonly problems of Nash reasoning: if everyone (or most people) did <strong>not</strong> do \(x\), everyone would be better off; and yet, a single person <strong>not</strong> doing \(x\) does not make much of a difference. Brian Hedden calls such acts \(exceptional\) acts because “the term is supposed to evoke the idea that in performing such an act, one seems to be making an exception for oneself” (531).</p>

<p>(To be more precise, this is just one subfamily of the larger family of collective action problems—namely, that of <cite>negative</cite> externalities, the canonical example being pollution; the other subfamily is that of <cite>positive</cite> externalities, the canonical example being the provision of a public good. Whether these two subfamilies are symmetric—and hence whether treating one subfamily entails treating the other—is a question I will bracket here and simply assume, with Hedden, that the argument applies to collective action problems plagued by negative externalities, rather than to collective action problems in general.)</p>

<p>The question in the background of this paper is then: Does consequentialism permit exceptional acts (and hence have undesirable action-guiding implications in collective action problems)? Consequentialists say (typically) no, critics say (typically) yes. Hedden takes two prominent consequentialist defenses:</p>

<p style="padding-left:100px;">“First, in triggering cases, the exceptional act is impermissible because it has submaximal expected value. It has a high probability of making things slightly worse, or a low probability of making things much worse, or something in between, but in any case its expected value will be lower than that of not performing the exceptional act. Second, all collective action problems are triggering cases.” (531–532)</p>

<p>For each of these defenses, Hedden comes up with novel objections (or rather novel revisions of existing objections) and then argues that these objections fail. This, ultimately, should be good news for the consequentialist. Here, I will focus on the second consequentialist defense and Hedden’s subsequent objection and counter-objection.</p>

<p style="padding-left:100px;"><u>All collective action problems are triggering cases</u></p>

<p>The second consequentialist defense is that “all collective action problems are triggering cases” (540). Here is how Hedden defines a triggering case:</p>

<p style="padding-left:100px;">“there is always some threshold number of people \(k\) such that the outcome would be worse if at least \(k\) people performed a given exceptional act than if fewer did so.” (540)</p>

<p>The paper then presents some canonical thought experiments that “put pressure” (540) on the claim that all collective action problems are triggering cases. Hedden’s main argument here employs a ‘money-pump’ case (borrowed from Parfit) although the paper never really refers to the vast money-pump literature, particularly in formal philosophy. This is puzzling because much of the reasoning in this section has been tackled with, what seems to me, more clarity in that literature (cf. especially Johan E. Gustafsson’s work that oddly doesn’t appear in the paper, as well as the substantial literature it has spurred; Akshath Jitendranath’s current doctoral work synthesises this literature). And this also includes the entire section on Ruth Chang’s parity. In any case, I’ll leave these issues aside.</p>

<p>The puzzle that will take up the rest of this note is the following. Hedden presents the consequentialist critic’s objection as saying ‘not all collective action problems are triggering cases’. Why? Because we can envision cases where there is no clear <strong>number</strong> of people \(k\) who tip one outcome into another. Now, clearly such an objection depends entirely on how one defines a triggering case. And given the above, very narrow, definition, it is unsurprising that many cases are left out. In any case, this will serve as a welcome opportunity to think through what a triggering case is with a bit more care.</p>

<p style="padding-left:100px;"><u>Defining the threshold of triggering cases</u></p>

<p>Let’s step back and define what a triggering case is more generally. Before that, we need to set up some preliminaries and define what a threshold is.</p>

<p>Suppose that there are \(n\) individuals and that each individual’s action set \(S\) consists of two actions: to \(x\) or not to \(x\), \(S = \{x, \neg x\}\). (So everyone’s action sets are identical.) An action profile is an \(n\)-tuple with a specific action for each agent: \(\mathbf{a} = (a_{1}, \dots, a_{n}) \in S^{n}\) where \(a_{i} \in \{x, \neg x\}\) for all \(i = 1, \dots, n\). To simplify notation, let \(\mathbf{a}_{K}\) denote the action profile where the first \(k\) agents do \(x\) and the rest of the \(n-k\) agents do \(\neg x\).</p>

<p>Further, let \(o: S^{n} \rightarrow \mathbb{R}\) be an outcome function which takes as an argument some action profile and assigns it a real number. For example, if the context is that of pollution, \(o(\mathbf{a}_{\{1, 2\}}) = 10\) denotes the case where when two people pollute, that leads to a pollution level of ten (whatever the relevant metric of pollution is).</p>

<p>A triggering case can now be defined as follows:</p>

<p style="padding-left:100px;"><strong>Triggering case</strong>. Let \(p \in \mathbb{R}\) be a scalar. Further, let \(T \subseteq N\) be a subset of the set of agents \(N\) and let \(U \subseteq N \setminus T\) be a subset of the complement of \(T\). Then, the tuple \((N, S^{n}, o, p, T, U)\) is a triggering case if and only if:</p>

<p style="padding-left:100px;">\(o(\mathbf{a}_{U})<p\) and \(o(\mathbf{a}_{U \cup T}) \geq p\).</p>

<p>In this definition, \(p\) is the threshold of perceptible or non-negligible relevant harm (for example, pollution, or pain). Then, a triggering case is a case where there is some collection of people \(U \cup T\) who are sufficient for the outcome to be of non-negligible level such that if the \(T\)-coalition refrained from performing the action, that would tip the level below the perceptibility threshold \(p\). As an illustration, recall Hedden’s definition above. In that definition, the collection of agents \(U \cup T\) is any collection of \(k\) agents and the set \(U\) is any collection of \(k - 1\) agents. Thus: \(T = \{i\}\) for any \(i \in N\) and \(U\) is any set of agents with cardinality \(k-1\).</p>

<p>(Note that there is an underlying anonymity axiom assumed in the above, which need not concern us here.)</p>

<p>What is important to notice here is that Hedden’s definition is a very special case of the more general definition above: namely, when the threshold coalition \(T\), which can tip the outcome to a non-negligible level, is a <cite>singleton</cite>. There is nothing particularly peculiar to triggering cases with non-singleton threshold coalitions. In fact, much of the causation literature, particularly <a href="https://doi.org/10.1007/s10670-009-9184-8" target="_blank" rel="noopener">that</a> concerned with variations of the so-called NESS test, has dealt with such coalitions. The upshot of that literature with respect to the discussion of collective action here can be summarised as follows: an individual might not be sufficient to trigger an outcome above a certain threshold, but that is no bad news for the consequentialist as long as an individual can belong to a (minimally) sufficient threshold coalition such as \(T\). Given appropriate probabilities, the possibility of belonging to such a coalition entails the possibility of bringing about great harm/pollution/etc. And thus, <cite>given an appropriately general definition of triggering cases</cite>, consequentialists may not permit performing the respective action. And they may not permit it precisely because the more general definition subsumes all possible triggering cases.</p>

<p>A consequentialist critic might object that \(T\) does not exist, but that is implausible: \(T\) may be a coalition of any size ranging from one to \(n\). And, given that in realistic cases, as Hedden also notes, the set of agents is a finite set of non-divisible entities, it is hard to see how \(T\) can fail to be a closed and bounded set that exists. A more plausible, indeed to my mind the most plausible, objection concerns the threshold \(p\).</p>
