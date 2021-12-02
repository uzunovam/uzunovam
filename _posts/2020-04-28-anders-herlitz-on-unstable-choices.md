---
layout: post
title: "Anders Herlitz on unstable choices"
date: 2020-04-28
---
<p>Anders Herlitz (2020). <a href="https://doi.org/10.1017/S0266267119000026" target="_blank" rel="noopener">Stable and unstable choices</a>. <cite>Economics & Philosophy</cite> 36 (1): 113–125.</p>

<p style="padding-left:100px;"><cite>John’s ice-cream</cite>: “Consider a variation of a joke retold by Larry Temkin: imagine a man, John, who enters an ice-cream parlour and proclaims: ‘I’ll have the strawberry, unless I’ve already chosen that – in which case I’ll go for chocolate! But if I’ve chosen chocolate, then I’ll have the strawberry!’ (<a href="https://doi.org/10.1093/acprof:oso/9780199759446.001.0001" target="_blank" rel="noopener">Temkin</a> 2012: 388). John appears to be irrational. He clearly wants strawberry ice-cream, but as soon as he has chosen it he does not want it any longer. Yet when he has changed his mind, he is again unsatisfied with his choice and wants to go back to strawberry. This paper presents a general condition that reflects the intuition that John is irrational and that explains why his behaviour is irrational.” (113)</p>

<p>By recalling the joke, Anders Herlitz invites us to focus not on the question whether John’s behaviour is irrational but, granting that it is, on the question why: what is it that makes John’s cylcing through the strawberry-chocolate-strawbery vertigo an instance of irrational behaviour? After discarding a number of candidates, the paper offers just such an explanation. In its shortest form, it claims that</p>

<p style="padding-left:100px;">“it is irrational to accept a normative theory or a decision method that implies
that the act of choosing a maximal alternative alone can revert whether this choice is maximal or not according to the theory.” (114)</p>

<p>And, more precisely, John’s behaviour is irrational because it follows a decision method that violates a novel, in Herlitz’ words,‘stability condition’. It is an interesting proposal; understanding it, however, requires some heavy preliminary reconstruction work. </p>

<p style="padding-left:100px;"><u>Reconstructing Herlitz’ argument</u></p>

<p>Herlitz’ starting point is that the features of an alternative that are relevant to how that alternative is evaluated by a theory or a method should be (explicitly, one may add) <cite>individuated</cite>. For example, if according to a utlitarian theory, the relevant ground for choice is ‘(maximum) utility’, then the utilities resulting from going for each alternative should be explicitly individuated. For some theories, however, ‘grounds for choice’ is not a static concept. As Herlitz puts it:</p>

<p style="padding-left:100px;">“Some decision methods and normative theories imply that making a choice changes the pertinent grounds for making a choice.” (117)</p>

<p>And if this is so, then this choice-dependence needs to be explicitly incorporated in how alternatives are individuated. Herlitz introduces the idea of <cite>transmutation</cite> as a way of capturing this transformative element of choice. Here is Herlitz’ way of phrasing it:</p>

<p style="padding-left:100px;">“A transmutation\(_{X}\) of an alternative, \(Y\), in a set of alternatives, \(C\), of which both \(X\) and \(Y\) are elements, into a transmuted\(_{X}\) alternative, \(Y_{X}\), is the transmutation of \(Y\) that appears in the choice set, \(C_{X}\), that is the set of alternatives \(C\) in which the negative and positive values associated with choosing \(X\) have been dispersed across the alternatives in \(C\).” (117)</p>

<p>And here is my attempt at formulating it a bit more precisely. For some preliminaries, suppose that \(X\) is the universal set of alternatives and let \(\mathcal{P}\) be the set of all (for simplicity, non-empty) subsets of \(X\); that is, the set of all possible agendas. (I set aside the question of whether all agendas are feasible as it is not central to Herlitz’ discussion.) A choice function \(C: \mathcal{P} \rightarrow X\) such that \(C(A) \subseteq A\) for all \(A \in \mathcal{P}\) tells us which element (or elements) of an agenda \(A\) has been chosen. Herlitz restricts his discussion to single-valued choice functions so let us add the restriction: \(|C(A)|=1\) for all \(A \in \mathcal{P}\).</p>

<p>The idea underlying transmutation then is that once a choice has been made, alternatives are transformed in some way. Suppose that an agenda \(A\) includes two alternatives, \(A = \{x, y\}\), and that the agent chooses \(x\). This then transform the agenda into \(A_{x} = \{x_{x}, y_{x}\}\). These new alternatives are still the old alternatives but with frills: they now include information about any negative or positive values accruing to them in the process of choosing. We can thus think of transmutation as another mapping—from the set of available options in an agenda to a bundle of two alternatives, \(T_{C(A)}: \mathcal{P} \rightarrow X \times X\), with the restriction that</p>

<p style="padding-left:100px;">\(T_{C(A)}(A) = \{(z, w) \ | \ z \in A \text{ and } \{w\} = C(A)\} \text{ for all } A \in \mathcal{P}\).</p>

<p>Suppose as before that the agent chooses \(x\), that is, \(C(A) = \{x\}\). Then, the transmutation function \(T_{x}(\cdot)\) changes the alternatives \(x\) and \(y\) into \((x, x)\) and \((y, x)\). That is to say, a transmutation is always relative to a choice function.</p>

<p>Herlitz’ main argument needs some more machinery. The argument is about normative theories or decision methods and while it doesn’t specify what precisely these are, his discussion suggests a way of defining them. Theories and methods set standards or principles that a choice needs to satisfy. For example, a utilitarian theory would involve a standard of maximisation. Herlitz himself speaks of maximality (being no worse than any other alternative) but nothing prevents us from being more general. Let a standard be a (choice) function \(S: \mathcal{P} \rightarrow X\) that picks out certain alternatives from the agenda with the restriction that \(S(A) \subseteq A\) for all \(A \in \mathcal{P}\). A normative theory or a decision method can then be defined as a set of \(k\) standards \(\{S_{1}, \dots, S_{k}\}\). Herlitz restricts his attention to single-standard (maximality) theories so for now let’s follow suit.</p>

<p>Now for Herlitz’ main argument. It is devoted to defending a type of invariance condition called <cite>stability</cite>. Here is Herlitz:</p>

<p style="padding-left:100px;">“A decision method/normative theory, \(P\), meets the stability condition if and only if it is always true according to the method/theory that if an option, \(X\), that according to the method/theory is maximal (i.e. not worse than any alternative) in a set of alternatives, \(C\), is chosen, then the transmutation\(_{X}\) of \(X\), \(X_{X}\), is also maximal according [to] \(P\) in \(C_{X}\), the set of alternatives consisting of the transmuted\(_{X}\) alternatives in \(C\).” (118)</p>

<p>And here again is my attempt at translation. Stability, note, is a property of a theory or method and since we have identified those with their unique standards, we can define stability as follows:</p>

<p style="padding-left:100px;"><strong>Stability</strong>. A standard \(S\) is stable if and only if:</p>

<p style="padding-left:100px;">if \(x \in S(A)\) and \(C(A) = \{x\}\), then \(T_{x}(x) \in S(T_{x}(A))\).</p>

<p>Suppose that the standard is maximality. Then it satisfies stability if alternative \(x\) is maximal in the original agenda and when \(x\) is chosen, the transmuted alternative \((x, x)\) is maximal in the transmuted agenda. Here is an example. Suppose that a maximal alternative is a no-worse alternative according to an underlying preference relation and that we have the following preferences over three alternatives:</p>

<p style="padding-left:100px;">Agenda \(A\): \(x \sim y \succ z\)</p>

<p style="padding-left:100px;">Agenda \(T_{x}(A)\): \((x, x) \succ (y, x) \succ (z, x)\)</p>

<p>Now, we have \(S(A) = \{x, y\}\) and \(C(A) = \{x\}\), and importantly \(T_{x}(x) = (x, x) \in S(T_{x}(A)) = \{(x, x)\}\). Hence, stability is satisfied.</p>

<p>If we had additionally:</p>

<p style="padding-left:100px;">Agenda \(T_{y}(A)\): \((x, x) \succ (y, x) \succ (z, x)\)</p>

<p>Then stability would be violated. Why? Because even though \(y\) is maximal in the original agenda (\(y \in S(A)\)), it is no longer maximal in the transmuted agenda <cite>given that \(y\) has been chosen</cite> (\(y \notin S(T_{y}(A)) = \{(x, x)\}\)).</p>

<p>For another example, let’s revisit <cite>John’s ice-cream</cite>. How does the idea of stability help us explain the intuition that John’s behaviour is irrational? The set of alternatives in this case consists of the strawberries and the chocolate, \(A = \{s,c\}\). When first asked, John says he will choose the strawberries and hence \(C(\{s,c\}) = \{s\}\). We may assume that his preferences are captured by \(s \succ c\). <cite>Once</cite> he has chosen the strawberries, however, he says that, if asked again, he’d choose the chocolate, that is, \(T_{s}(\{s,c\}) = \{(s,s),(c,s)\}\) and \((c,s) \succ (s,s)\). (And so on.) If the relevant standard \(S\) is ‘choose the maximal element’ (if any), then \(s \in S(\{s,c\})\) but \((s,s) \notin S(T_{s}(\{s,c\}))\). And hence John is using a standard (maximality), or a normative theory, such that choosing the maximal alternative according to this standard, \(s\), may lead to its transmutation \((s,s)\) not being maximal according to that very same standard (in the transmuted agenda).</p>

<p>A note before proceeding: when Herlitz speaks of maximality, he really means maximality with respect to the relevant theory or method (or, in the language above, standard). Maximality doesn’t have to mean maximal element with respect to one’s preferences, as in the illustrations above. Nothing much hinges on this. The relations above may be interpreted as standard-specific relations (rather than preferences). We then have maximality in Herlitz’ sense: the maximal element, if any, according to the specific standard represented by a relation.</p>

<p style="padding-left:100px;"><u>Violating stability: Transformative choices</u></p>

<p>Herlitz claims that theories or methods that violate stability are suspicious and should be avoided. Why? Because</p>

<p style="padding-left:100px;">“it is irrational to accept decision methods and normative theories that allow for the act of choosing a maximal alternative to render this alternative non-maximal”. (113)</p>

<p>There are a number of good reasons why stability may be a desirable property for a normative (particularly, action-guiding) theory or method—see pp. 119ff for this discussion.</p>

<p>But if satisfying the stability condition may be plausible or desirable, we may ask the inverse question: is violation of the stability condition implausible or undesirable? Examples of theories that violate stability are some strands of prioritarianism (121ff) but we need’t go further than more classical decision methods to find such examples. For instance, a standard rational choice model that allows for what Ruth Chang calls <a href="https://doi.org/10.11612/resphil.2015.92.2.14" target="_blank" rel="noopener"><cite>transformative choices</cite></a> violates stability. In Herlitz’ framework, a transformative choice would be a transmutation of the agenda such that the ‘best’ elements in the original agenda according to the theory’s standard may no longer be ‘best’ elements in the transmuted agenda. Particularly, this would be Chang’s second type of transformative choice, or what she refers to as a ‘choice-based’ transformative choice. Of course, there needn’t be anything irrational about such choices because experience is part and parcel of coming to evaluate certain alternatives. Think of a person’s preferences over agendas that include having a child: one can’t know it till one’s had it (or so parents say). If the concept of <cite>qualia</cite> is coherent, then transformative choices may be too ubiquitous to be classified as suspicious. (Though, of course, <a href="https://doi.org/10.1017/S0266267116000274" target="_blank" rel="noopener">people</a> have been suspicious.)</p>

<p>But Herlitz’ argument can’t be dismissed so lightly and indeed it cuts deeply. After all, it is not about individual <cite>choices</cite> but about normative <cite>theories</cite>. If a theory’s own standard tells you that there is a ‘best’ alternative, isn’t it irrational—by the theory’s own lights—if it were to tell you otherwise once you have chosen the alternative? You might say no precisely because the act of choosing might change the standard’s evaluation and we are back to the objection from transformative choices. I think this objection can be accommodated.</p>

<p>(For better or worse, Herlitz’ motivating example seems a bit misleading: it suggests that John has already tried both strawberry and chocolate ice-cream. This might be so but then when such choices violate stability, the underlying theory’s irrationality needn’t be controversial. Herlitz’ discussion throughout the text doesn’t mention but also doesn’t rule out transformative choices and this seems to be a much stronger challenge to the stability condition. A more interesting, but also less straightforward, example might have been the case of John who hasn’t tried strawberry ice-cream.)</p>

<p>A brute-force way of accommodating the objection is to restrict the permissible agendas to those consisting of alternatives that the agent has had experience with. A more refined way of dealing with the objection is to distinguish between <cite>choosing</cite> and <cite>doing</cite>. Most normative theories would count experience with the alternatives as relevant information in the process of evaluating them. This implies that the function, which denotes the relevant standard, should not be defined over the respective (initial or transmuted) agenda but over <cite>having experience</cite> with that agenda. One can easily define an experience function over the respective agenda and then require that the standard and choice functions are applied not to the agenda but to the experience agenda. Alternatively, if there is other relevant information, one could define not an experience but a broader information function over the agendas.</p>

<p>The objection from transformative choices is a strong objection against Herlitz’ stability condition but it is not fatal. Ultimately, it can be accommodated. There is, however, a further worry that might give us pause when evaluating theories on the basis of the stability condition.</p>

<p style="padding-left:100px;"><u>Violating stability: Hybrid normative theories</u></p>

<p>Herlitz’ discussion is restricted to single-standard theories and this would be fine were it to easily carry over to hybrid theories with multiple standards. But this doesn’t seem to be the case. Take a hybrid prioritarian-egalitarian theory which says: 1) as long as there are people below a certain threshold, maximise the welfare of the worst off; 2) as as soon as everyone is above the threshold, minimise inequality.</p>

<p>Suppose that there are two individuals and that the welfare threshold (for leading a good or a flourishing life on your preferred account) is four. Now consider these distributions where \(q\) is the status quo:</p>

<p style="padding-left:100px;"><cite>Case 1</cite>:</p>

<p style="padding-left:100px;">\(q = (3.5; 3)\)</p>

<p style="padding-left:100px;">\(r = (100; 4.1)\)</p>

<p style="padding-left:100px;">\(s = (1,000,000; 4.2)\)</p>

<p>Given that under the status quo, both agents are below the threshold, the theory says that we should maximise the welfare of the worst off, that is, of agent two. Thus, according to the theory’s first standard: \(S_{1}(\{q,r,s\}) = \{s\}\). But suppose that \(s\) is now the status quo:</p>

<p style="padding-left:100px;"><cite>Case 1 continued:</cite>:</p>

<p style="padding-left:100px;">\((q, s) = (1,000,000; 4.2)\)</p>

<p style="padding-left:100px;">\((r, s) = (100; 4.1)$</p>

<p style="padding-left:100px;">\((s, s) = (1,000,000; 4.2)$</p>

<p>Both agents are above the minimal threshold and now the theory’s second standard kicks in: \(S_{2}(\{(q, s), (r,s), (s, s)\}) = \{(r, s)\}\).</p>

<p>Whatever the theory’s other shortcomings, few people would perhaps contest that minimising such blatant inequality once everyone has enough is desirable. But what of the theory’s relation to the stability condition? It is not clear what the relation is, and the reason is that the condition is undefined when it comes to such hybrid theories. A straightforward extension to hybrid theories might go as follows:</p>












