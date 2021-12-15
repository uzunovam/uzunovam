---
layout: post
title: "Nicolas Côté on measuring freedom"
date: 2020-08-22
---
<p>Nicolas Côté (2020). <a href="https://doi.org/10.1086/707214" target="_blank" rel="noopener">Weakness of will and the measurement of freedom</a>. <cite>Ethics</cite> 130 (3): 384–414.</p>

<p>Nicolas Côté’s aim is ambitious: he wants to bring issues of the weakness of will front and centre in the debates on how freedom (of choice) should be measured. More precisely, if measures of freedom, as the literature has argued, must involve some <cite>comparison</cite> of the various sets of options available to agents, then these measures must also incorporate the issue of <cite>differential accessibility</cite>: some sets are less accessible than other sets and, at the limit, some sets are even inaccessible. Existing measures, Côté argues, are sensitive only to the limit cases of perfect accessibility and perfect inaccessibility. ‘Degrees of accessibility’ is thus Côté’s main contribution to the literature on the measurement of freedom, breaking the stark binary partition of accessibility vs inaccessibility into a more fine-grained continuum of accessibility.</p>

<p>Let us start with a case that Côté uses to motivate his approach:</p>

<p style="padding-left:100px;">“Consider first Weak-Willed Willy and Resolute Regina. Suppose that every night for a whole week both have the choice between four alternatives: completing job applications, solving logic problem sets, working on their essays, and going out to drink with friends. In other words, their opportunity sets are identical. Both would love nothing more than to go out with their friends, but they have resolved not to because this would adversely affect their capacity to meet urgent deadlines with respect to their work, and they both judge that meeting these deadlines is more important than enjoying themselves that week. Regina, being resolute, is pretty consistently successful in recruiting the motivation to resist temptation, and she is very skilled at shifting her attention toward cues that facilitate self-control. She is quite reliable: if she says she will do something, or that she judges that she ought to do it, it is generally a sure bet that she will. Willy, by contrast, is a flake, generally unsuccessful in resisting temptation when it presents itself, and unskilled at refocusing his attention. He is almost always carried away by his present urges to renege on his previously stated intentions and judgments.” (393–394)</p>

<p>Classical measures of freedom, based on less or more sophisticated ways of incorporating the cardinality of sets or the quality of their members, must conclude that the two agents are equally free: after all, both share identical opportunity sets, with an identical number of equally desirable identical members. And yet, Côté continues, intuitively we must say that Willy is less free than Regina is. (Let’s grant this.) How can that be? The reason for this freedom differential, Côté ultimately argues, is that the options are not equally accessible to each agent: Regina is very skilled at thwarting temptation and the options are, say, maximally accessible to her; Willy, on the other hand, cannot access these options so easily.</p>

<p>Côté presents this solution as a generalisation of the classical approach (406ff) which only admits of perfectly accessible or perfectly inaccessible options. By allowing for intermediate values of accessibility, we can explain how it is that Willy’s ‘total accessibility’ to the same set of (otherwise, not perfectly inaccessible) options is less than that of Regina’s. So far so good: we can grant that such a generalisation is possible and, admittedly as most generalisations are, valuable. Implicitly buried in Côté’s discussion, however, are issues of agent-neutrality and agent-relativity that merit bringing out more explicitly. For being more explicit about these issues grants even more generality to Côté’s approach. The remainder explains why.</p>

<p style="padding-left:100px;"><u>Preliminaries</u></p>

<p>Start with some preliminaries. Say that \(X\) is the (universal finite) set of all mutually exclusive options. Set \(Z\), the power set of \(X\), is the set of all possible opportunity sets. The relation \(\succeq\) is then a binary relation on \(Z\), that is, \(\succeq \subseteq Z \times Z\), that is transitive, nonsymmetric and reflexive (387). Thus, \(A \succeq B\) means (the opportunity set) \(A\) offers at least as much freedom as (the opportunity set) \(B\). The question now is: what kind of properties should \(\succeq\) satisfy so that the resulting (comparative) measure of freedom is a plausible one? (A question that Côté asks but does not go into with respect to his own approach.)</p>

<p>There are many existing measures motivated by, or argued against on the basis of, numerous properties (see Côté’s excellent discussion of the classical literature here). But they all, Côté argues, share one common feature that precludes incorporating the issue of differential accessibility: they all assume that set membership is bivalent. That is to say, that an option \(w\) either belongs to or does not belong to an opportunity set \(W\). It is this bivalence that Côté questions and then relaxes as a way of introducing a new measure that is sensitive to weakness-of-will issues.</p>

<p style="padding-left:100px;"><u>Côté’s proposal: Fuzzy freedom</u></p>

<p>In short, Côté’s proposal is to conceive of opportunity sets not as bivalent sets but as fuzzy sets. More precisely, say that an opportunity set is a pair, \((X, m)\), where \(X\) is the familiar set of all options and \(m\) is a membership function that maps each element of \(X\) on the unit interval. The scalar \(m(w)\) of an option \(w \in X\) is the option’s ‘membership grade’: in the classical bivalent case, an option can have only one of two grades—zero or one. Let \(Z^{*}\) collect all such pairs. Further, given a set \(W\), let \(\mu_{W}\) denote the set’s membership function. (Hence, by definition, \(m \equiv \mu_{X}\).) And let the cardinality of a set be defined as the sum of its elements’ membership grades: \(|W| = \sum_{w \in W} \mu_{W}(w)\).</p>

<p>Clearly, fuzzy sets expand the classical bivalent case where an option \(w\) in a set \(W\) can be either, as Côté’s puts it, “fully accessible” (when \(\mu_{W}(w) = 1\)), or “not available” (when \(\mu_{W}(w) = 0\)). Rather, an option can now also be “partially accessible” (when \(\mu_{W}(w) \in (0, 1)\)) (406). The substantive interpretation Côté gives of \(\mu_{W}(w)\) is that of “conditional probability”: “the chance that an agent can successfully choose [\(w\)] if they intend to” (407).</p>

<p>Let’s summarise the two approaches. In Côté’s fuzzy approach, we have:</p>

<p style="padding-left:100px;"><strong>Fuzzy freedom</strong>. Freedom (of choice) is a function of the accessibility of options in an agent’s opportunity set, where an agent’s opportunity set is a pair \((X, \mu_{X})\), with \(X\) being the respective universal set and \(\mu_{X}\) being the set’s membership function:</p>

<p style="padding-left:100px;">\(\mu_{X}: X \rightarrow [0, 1]\)</p>

<p>It’s a generalisation of the classical approach where the only difference is the definition of \(\mu_{X}\):</p>

<p style="padding-left:100px;"><strong>Classical freedom</strong>. Freedom (of choice) is a function of the accessibility of options in an agent’s opportunity set, where an agent’s opportunity set is a pair \((X, \mu_{X})\), with \(X\) being the respective universal set and \(\mu_{X}\) being the set’s membership function:</p>

<p style="padding-left:100px;">\(\mu_{X}: X \rightarrow \{0, 1\}\)</p>

<p>So far so good. How do the two approaches handle the case of Regina and Willy? All things equal (the quality and desirability of options, say), that is to say, when set membership is the only issue relevant to freedom, Côté claims, the two approaches fare differently. This, however, is not true; at least not with the machinery introduced so far. Notice that, in Côté’s framework (outlined above), membership functions are set-specific (I used \(\mu_{X}\) instead of \(m\) to underscore this): different sets have different membership functions. This is unobjectionable and it is indeed what allows Côté to generalise the ideas of cardinality and membership to fuzzy sets. However, what Côté needs in order to treat Regina’s and Willy’s cases differently are (additionally) agent-specific membership functions. In other words, we need to allow for the fact that <cite>for each set</cite>, there exists <cite>for each agent</cite> a membership function \(\mu_{X}^{i}\). Intuitively, this simply brings out explicitly the approach that Côté is at least implicitly getting at:</p>

<p style="padding-left:100px;"><strong>Fuzzy freedom*</strong>. Freedom (of choice) is a function of the accessibility of options in an agent’s opportunity set, where an agent’s opportunity set is a pair, \((X, \mu_{X}^{i})\), with \(X\) being the respective universal set and \(\mu_{X}^{i}\) being the set’s membership function <cite>for the agent</cite>:</p>

<p style="padding-left:100px;">\(\mu_{X}^{i}: X \rightarrow [0, 1]\)</p>

<p style="padding-left:100px;"><strong>Classical freedom*</strong>. Freedom (of choice) is a function of the accessibility of options in an agent’s opportunity set, where an agent’s opportunity set is a pair, \((X, \mu_{X}^{i})\), with \(X\) being the respective universal set and \(\mu_{X}^{i}\) being the set’s membership function <cite>for the agent</cite>:</p>

<p style="padding-left:100px;">\(\mu_{X}^{i}: X \rightarrow \{0, 1\}\)</p>

<p>Now, consider Regina’s and Willy’s cases again. How does classical freedom* handle these cases? We know that, by assumption, we have \(\sum_{w \in X} \mu_{X}^{R}(w) = \sum_{w \in X} \mu_{X}^{W}(w)\). For Regina and Willy to have identical options (fully) available to them—or, put differently, for \(\mu_{X}^{R}\) and \(\mu_{X}^{W}\) to assign non-zero weights to the same options—the agents must have identical membership functions: \(\mu_{X}^{R} = \mu_{X}^{W}\). And this, in turn, implies that the agents must have the same opportunity sets: \((X, \mu_{X}^{R}) = (X, \mu_{X}^{W})\).</p>

<p>The same, in contrast, is not true of the fuzzy approach. Under fuzzy freedom*, \(\mu_{X}^{R}\) and \(\mu_{X}^{W}\) can assign non-zero weights to the same options while the functions are different, \(\mu_{X}^{R} \neq \mu_{X}^{W}\), and hence while the opportunity sets are different, \((X, \mu_{X}^{R}) \neq (X, \mu_{X}^{W})\).</p>

<p>One might say that this simply brings out the stark contrast between binary vs non-binary weights. But it is useful to summarise the conclusions of the two approaches once again: if the agents’ membership functions assign non-zero weights to the same options, then classical freedom*—unlike fuzzy freedom*—implies that the agents’ membership functions and hence their opportunity sets are identical. <cite>Put differently, agent neutrality is a necessary condition for assigning positive weights to the same options under classical freedom* but not under fuzzy freedom*.</cite> Or, put yet differently, agent neutrality is a necessary condition for options being equally accessible under classical freedom* but not under fuzzy freedom*.</p>

<p style="padding-left:100px;"><u>Assessing agent-centricity</u></p>

<p>The richness and generality of Côté’s approach can now come out even more vividly. For it effectively allows for predicating accessibility, and hence freedom, on resource-based considerations. (Classical approaches have normally allowed for agential heterogeneity by way of preferences. Côté’s approach is novel, in this sense, in extending heterogeneity to abilities and hence to the accessibility of options.) Indeed, while Côté’s proposal is framed as tackling freedom of will issues, it’s value in fact is much deeper.</p>

<p>Consider two agents, \(A\) and \(B\). While the two have identical preferences, \(A\) has more resources than \(B\). Suppose further that, given the universal set of options \(X\), the agents’ membership functions assign non-zero weights to the same options: for all \(w \in X\): \(\mu_{X}^{A}(w) \neq 0\) if and only if \(\mu_{X}^{B}(w) \neq 0\). Now, classical freedom* implies that the two agents have equal access to their relevant options. To put the matter in slightly Marxist terms, classical freedom* obscures the underlying socio-economic differences between the otherwise similarly situated agents—differences that might be relevant to the options’ differential accessibility and hence the agents’ freedom. (To make the case more plausible, one might assume that, while poorer overall, \(B\) can work harder and longer than \(A\) has to but can still gain access to the same options.) In this sense, fuzzy freedom* is not just useful in its ability to account for the weakness of will—it allows for grounding measures of freedom on considerations related to equality of opportunity. Indeed, it allows for integrating such considerations into the very measure of freedom.</p>

<p>In a way, I see Côté’s framing of his approach around issues of the weakness of will unfortunate: this runs the risk of restricting the (perceived) utility of the analysis to subjective factors. Its real force, to my mind, is in its ability to expand measures of freedom to much more socially, and even structurally, determined factors. One set of questions that are yet to be broached with respect to the latter issue is the following: what kind of properties should such a socially grounded measure of freedom satisfy? And how do they differ from existing properties commonly imposed on classical measures that do not allow for differential abilities grounding differential access? Answers to these questions will pave the way towards examining the normative intuitions that support various subjectivist vs social or structuralist conceptions and measures of freedom.</p>

<p style="padding-left:100px;"><u>Revisiting Pattanaik and Xu</u></p>

<p>Let’s give it a try by revisiting the original characterisation of the classical cardinal measure of freedom by <a href="https://www.jstor.org/stable/40723933" target="_blank" rel="noopener">Pattanaik and Xu</a>, but this time within Côté’s generalised framework. That is to say, consider how we can characterise the <cite>generalised</cite> cardinal measure. To make this framework more tractable, start by assuming a (finite) universal set of options \(X\). Then, define the opportunity set of agent \(i\) to be a pair, \((X, \mu_{X}^{i})\), where \(\mu^{i}_{X}\) is the agent’s set membership function. For simplicity, when the relevant set is the universal set \(X\), I will suppress the subscript and simply refer to \(\mu^{i}_{X}\) as \(\mu^{i}\).</p>

<p>Technically, \(\mu^{i}\) can be any function. The two approaches can now be distinguished by the type of \(\mu^{i}\) they assume:</p>

<p style="padding-left:100px;"><strong>Fuzzy membership function</strong>. An agent’s fuzzy set membership function, \(f^{i}\), is:</p>

<p style="padding-left:100px;">\(f^{i}: X \rightarrow [0, 1]\)</p>

<p style="padding-left:100px;"><strong>Classical membership function</strong>. An agent’s fuzzy set membership function, \(c^{i}\), is:</p>

<p style="padding-left:100px;">\(c^{i}: X \rightarrow \{0, 1\}\)</p>

<p>Fuzzy freedom* can then be characterised by its definition of \((X, \mu^{i})\) as \((X, f^{i})\), while classical freedom* can be characterised by its definition of \((X, \mu^{i})\) as \((X, c^{i})\).</p>

<p>Let \(Z\) collect the opportunity sets of all agents. A measure of freedom, or more appropriately, a freedom ranking, is a binary relation on the set of agential opportunity sets, \(\succeq \subseteq Z \times Z\). (We can denote by \(\succeq_{c}\) (\(\succeq_{f}\)) the classical (fuzzy) relation defined on the set of classical (fuzzy) opportunity set \(Z_{c}\) (\(Z_{f}\)). Although this will be unnecessary notation in what follows.)</p>

<p>Now, let’s define a generelised simple cardinality-based ordering:</p>

<p style="padding-left:100px;"><strong>Generalised simple cardinality-based ordering (GSCO)</strong>. \(\succeq\) will be called a GSCO if and only if for all agent-centric opportunity sets, \((X, \mu^{i}), (X, \mu^{j}) \in Z\), we have:</p>

<p style="padding-left:100px;">\((X, \mu^{i}) \succeq (X, \mu^{j})\) if and only if \(\sum_{w \in X} \mu^{i}(w) \geq \sum_{w \in X} \mu^{j}(w)\)</p>

<p style="padding-left:100px;">For simplicity, we might introduce the following notation: \(|(X, \mu^{i})| = \sum_{w \in X} \mu^{i}(w)\). A GSCO can then be defined as:</p>

<p style="padding-left:100px;">\((X, \mu^{i}) \succeq (X, \mu^{j})\) if and only if \(|(X, \mu^{i})| \geq |(X, \mu^{j})|\)</p>

<p>A GSCO simply ranks agent-centric opportunity sets according to their cardinality. (Notice, however, that Côté’s approach makes it much more explicit that we are ranking the freedom levels of different agents. Alternatively, ranking the freedom levels of the same agent across time, and hence of different selves of the same agent, would be formally equivalent.) We can distinguish between the fuzzy and the classical variety:</p>

<p style="padding-left:100px;"><strong>Fuzzy simple cardinality-based ordering (FSCO)</strong>. \(\succeq\) will be called a FSCO if and only if \(\succeq\) is a GSCO and for all agents \(i \in N\):</p>

<p style="padding-left:100px;">\(\mu^{i} = f^{i}\)</p>

<p style="padding-left:100px;"><strong>Classical simple cardinality-based ordering (CSCO)</strong>. \(\succeq\) will be called a CSCO if and only if \(\succeq\) is a GSCO and for all agents \(i \in N\):</p>

<p style="padding-left:100px;">\(\mu^{i} = c^{i}\)</p>

<p>A little extra notation will be useful before proceeding to the axioms we will consider. Consider an agent’s opportunity set, \((X, \mu^{i})\). The agent’s membership function \(\mu^{i}\) assigns non-zero weights to some members and zero weights to others: partition \(X\) so that \(X_{+}^{i} \subseteq X\) collects the former and \(X_{0}^{i} \subseteq X\) collects the latter. (Clearly, \(X_{+}^{i} \cup X_{0}^{i} = X\).) Further, let \(\mathbf{a}_{+}^{i}\) be a vector, collecting the non-zero weights of the members of \(X_{+}^{i}\) and let \(\mathbf{a}_{0}^{i}\) be a (zero) vector, collecting the zero weights of the members of \(X_{0}^{i}\). To simplify notation, I will refer to an opportunity set not as \((X, \mu^{i})\) but as \((X, X_{+}^{i}, \mathbf{a}_{+}^{i})\). This allows as to focus on positively weighted elements when comparing the freedom of various agents. That is to say, it allows us to focus on those options that are actually available (to some degree) to agents. To further simplify notation, I will omit the reference to the universal set (when there is no variation across universal sets, and there won’t be in the remainder of this) and refer to \((X, X_{+}^{i}, \mathbf{a}_{+}^{i})\) as \((X_{+}^{i}, \mathbf{a}_{+}^{i})\). In short, here I will be concerned only with freedom comparisons across agents given that agents face the same universal set.</p>

<p>Consider now a possible restatement of Pattanaik and Xu’s three axioms, in the generalised framework. Suppose, first, that agents are faced with a single positively weighted option: \(|X^{i}_{+}| = |X^{j}_{+}| = 1\). Suppose that \(X^{i}_{+} = \{x\}\) and \(X^{j}_{+} = \{y\}\) and, further, that the weight each agent’s membership function assigns to these single elements is \(a^{i}\) and \(a^{j}\), respectively. The opportunity sets for the two agents in this case of a single positively weighted option are: \((\{x\}, a^{i})\) and \((\{y\}, a^{j})\). Pattanaik and Xu’s first axiom can now be restated as:</p>

<p style="padding-left:100px;"><strong>Indifference between no-choice situations (a) (INSa)</strong>. \(\succeq\) satisfies INSa when for all \(x, y \in X\):</p>

<p style="padding-left:100px;">\((\{x\}, a^{i}) \sim (\{y\}, a^{j})\) if and only if \(a^{i} = a^{j}\)</p>

<p>INSa generalises Pattanaik and Xu’s original axiom that concerns indifference in the case of <cite>perfect</cite> accessibility to indifference in the case of <cite>equal</cite> accessibility.</p>

<p>Consider next a variant of Pattanaik and Xu’s second axiom:</p>

<p style="padding-left:100px;"><strong>Monotonicity (MON)</strong>. Take two pairs of opportunity sets: \((X^{i}_{+}, \mathbf{a}_{+}^{i})\) and \((X^{j}_{+}, \mathbf{a}_{+}^{j})\), and \((Y^{i}_{+}, \mathbf{b}_{+}^{i})\) and \((Y^{j}_{+}, \mathbf{b}_{+}^{j})\). Suppose that the latter pair differs from the former in that an equal amount has been added to all membership grades of the two agents. Then \(\succeq\) satisfies MON when for all such pairs the following two hold:</p>

<p style="padding-left:100px;">(1) \((X^{i}_{+}, \mathbf{a}_{+}^{i}) \succeq (X^{j}_{+}, \mathbf{a}_{+}^{j})\) if and only if \((Y^{i}_{+}, \mathbf{b}_{+}^{i}) \succeq (Y^{j}_{+}, \mathbf{b}_{+}^{j})\)</p>

<p style="padding-left:100px;">(2) \((X^{i}_{+}, \mathbf{a}_{+}^{i}) \succ (Y^{i}_{+}, \mathbf{b}_{+}^{i})\) and \((X^{j}_{+}, \mathbf{a}_{+}^{j}) \succ (Y^{j}_{+}, \mathbf{b}_{+}^{j})\)</p>

<p>Next, take a version of Pattanaik and Xu’s third axiom:</p>

<p style="padding-left:100px;"><strong>Independence (a) (INDa)</strong>. Take two opportunity sets, \((X_{+}^{i}, \mathbf{a}_{+}^{i})\) and \((X_{+}^{j}, \mathbf{a}_{+}^{j})\), and consider two options (not necessarily distinct) that are inaccessible to both agents: \(x, y \in X \setminus \{X_{+}^{i} \cup X_{+}^{j}\}\). \(\succeq\) satisfies INDa when for all opportunity sets and for all such inaccessible options \(x, y\):</p>

<p style="padding-left:100px;">\((X_{+}^{i} \cup \{x\}, \mathbf{b}^{i}_{+}) \succeq (X_{+}^{j} \cup \{y\}, \mathbf{b}_{+}^{j})\) if and only if \((X^{i}_{+}, \mathbf{a}^{i}_{+}) \succeq (X^{j}_{+}, \mathbf{a}^{j}_{+})\) and \(\mu^{i}(x) \geq \mu^{j}(y)\)</p>

<p>We need an extra axiom to characterise the generalised cardinal measure:</p>

<p style="padding-left:100px;"><strong>Distribution independence (DI)</strong>. Take two opportunity sets, \((X_{+}^{i}, \mathbf{a}_{+}^{i})\) and \((X_{+}^{j}, \mathbf{a}_{+}^{j})\) that have a different cardinality. Now, take two transformations of the sets such that \(X_{+}^{i}\) and \(X_{+}^{j}\) remain unchanged, but the membership functions of each agent equalise their respective membership grades across all positively accessible options. That is to say, the membership grade of each option available to \(i\) now becomes: \(|(X_{+}^{i}, \mathbf{a}_{+}^{i})| \setminus |X^{i}_{+}|\). (Similarly, for \(j\).) Denote these two equalising transformations by \((X^{i}_{+}, \mathbf{e}^{i}_{+})\) and \((X^{j}_{+}, \mathbf{e}^{j}_{+})\), respectively. Then, \(\succeq\) satisfies DI when for all opportunity sets and their equalising transformations:</p>

<p style="padding-left:100px;">\((X_{+}^{i}, \mathbf{a}^{i}_{+}) \succeq (X_{+}^{j}, \mathbf{a}_{+}^{j})\) if and only if \((X_{+}^{i}, \mathbf{e}^{i}_{+}) \succeq (X_{+}^{j}, \mathbf{e}_{+}^{j})\)</p>

<p>Clearly, DI expresses the intuition that the distribution of membership grades does not matter: what matters is the total sum of the grades—or, put differently, the cardinality of the opportunity sets.</p>

<p>The first thing to notice from this restatement of the axioms in Côté’s generalised framework is that the axioms have severe restrictions on the membership functions—and hence <cite>severe cardinality restrictions</cite>—baked into them. This might feel like cheating but, intuitively, it simply makes Pattanaik and Xu’s original characterisation of the cardinal measure not so surprising.</p>

<p>Now we can show a result analogous to the one by Pattanaik and Xu:</p>

<p style="padding-left:100px;"><strong>Proposition</strong>. \(\succeq\) satisfies INSa, MON, INDa, and DI if and only if it is the GSCO.</p>

<p>Notice here that this is a characterisation of GSCO, and not of its special varieties, be it the fuzzy or classical one. To obtain the special fuzzy variety, one would need to impose further normalisation conditions on the function (so that grades fall in the unit interval). This will not be pursued here.</p>

<p style="padding-left:100px;"><cite>Proof</cite>: The GSCO clearly satisfies the axioms.</p>

<p style="padding-left:100px;">What needs to be proved is the following:</p>

<p style="padding-left:100px;">For all opportunity sets \((X_{+}^{i}, \mathbf{a}_{+}^{i}), (X_{+}^{j}, \mathbf{a}_{+}^{j}) \in Z\):</p>

<p style="padding-left:200px;">If \(|(X_{+}^{i}, \mathbf{a}_{+}^{i})| \geq |(X_{+}^{j}, \mathbf{a}_{+}^{j})|\), then \((X_{+}^{i}, \mathbf{a}_{+}^{i}) \succeq (X_{+}^{j}, \mathbf{a}_{+}^{j})\)</p>

<p style="padding-left:100px;">Like Pattanaik and Xu, I break this down into two parts:</p>

<p style="padding-left:200px;">If \(|(X_{+}^{i}, \mathbf{a}_{+}^{i})| = |(X_{+}^{j}, \mathbf{a}_{+}^{j})|\), then \((X_{+}^{i}, \mathbf{a}_{+}^{i}) \sim (X_{+}^{j}, \mathbf{a}_{+}^{j}) \quad\) (1)</p>

<p style="padding-left:200px;">If \(|(X_{+}^{i}, \mathbf{a}_{+}^{i})| > |(X_{+}^{j}, \mathbf{a}_{+}^{j})|\), then \((X_{+}^{i}, \mathbf{a}_{+}^{i}) \succ (X_{+}^{j}, \mathbf{a}_{+}^{j}) \quad\) (2)</p>

<p style="padding-left:100px;">(1) Pattanaik and Xu prove (1) by induction but in the generalised framework this is no longer possible. To see why, notice that now it is possible to have two opportunity sets with the same cardinality such that \(|X_{+}^{i}| \neq |X_{+}^{j}|\). This means that agents can have an identical accessibility while having (positive) accessibility to an <cite>unequal</cite> number of options. This is a significant departure from the classical cardinal measure. Why? Because it allows us to say that an agent with a single <cite>perfectly</cite> accessible option is more free than another agent with a number of <cite>im</cite>perfectly accessible options. Intuitively, in these limit cases, the generalised cardinal measure shifts our intuitions from the number of available options to the degree, or <cite>quality</cite>, of accessibility to these options. And it allows us to test our intuitions on the kind of trade-offs we believe can be plausibly made between the number of available options and the quality of availability involved. (Alternatively, one can think of the classical cardinal measure as having a <cite>ceteris paribus</cite> clause such that it holds the quality of accessibility fixed, allowing intuitions to vary only over the number of options.)</p>

<p style="padding-left:100px;">So we need a different strategy. Take two arbitrary opportunity sets with the same cardinality. There are two scenarios: either (i) \(|X_{+}^{i}| = |X_{+}^{j}| = k\), or (ii) \(|X_{+}^{i}| \neq |X_{+}^{j}|\).</p>

<p style="padding-left:150px;">(i) Suppose \(|X_{+}^{i}| = |X_{+}^{j}| = k\) is the case. For opportunity sets where \(k = 1\), by definition, equal cardinality implies \(a^{i} = a^{j}\) and hence, by INSa, we have: \((\{x\}, a^{i}) \sim (\{y\}, a^{j})\).</p>

<p style="padding-left:150px;">So suppose that for any integer \(n\) (and for any two opportunity sets with, remember, the same cardinality), if \(k = n\), then \((X_{+}^{i}, \mathbf{a}_{+}^{i}) \sim (X_{+}^{j}, \mathbf{a}_{+}^{j})\). Now, take two opportunity sets with the same cardinality, \((Y_{+}^{i}, \mathbf{b}_{+}^{i})\) and \((Y_{+}^{j}, \mathbf{b}_{+}^{j})\), such that \(|Y_{+}^{i}| = |Y_{+}^{j}| = n+1\). We need to show that \((Y_{+}^{i}, \mathbf{b}_{+}^{i}) \sim (Y_{+}^{j}, \mathbf{b}_{+}^{j})\).</p>

<p style="padding-left:150px;">Notice that this is no longer as straightforward as in Pattanaik and Xu’s original proof because removing positively weighted options does <strong>not</strong> preserve the cardinality of the agents’ <strong>opportunity</strong> sets. Now, there are two options here: either (i.1) \(Y_{+}^{i}\) and \(Y_{+}^{j}\) have a common element \(x\), or (i.2) they don’t.</p>

<p style="padding-left:200px;">(i.1) Suppose they do. Consider the restricted opportunity sets that result from removing \(x\): \((Y_{+}^{i} \setminus \{x\}, \mathbf{c}_{+}^{i})\) and \((Y_{+}^{j} \setminus \{x\}, \mathbf{c}_{+}^{j})\). Now, if the removal of \(x\) preserves cardinality, then \(\mu^{i}(x) = \mu^{j}(x)\) and, by the induction hypothesis and INDa, we have \((Y_{+}^{i}, \mathbf{b}_{+}^{i}) \sim (Y_{+}^{j}, \mathbf{b}_{+}^{j})\). Suppose that the removal of \(x\) does not preserve cardinality so that, without loss of generality, \(\mu^{i}(x) > \mu^{j}(x)\). We now have \(|(Y_{+}^{i} \setminus \{x\}, \mathbf{c}_{+}^{i})| < |(Y_{+}^{j} \setminus \{x\}, \mathbf{c}_{+}^{j})|\) and, by assumption, \(|(Y_{+}^{i}, \mathbf{b}_{+}^{i})| = |(Y_{+}^{j}, \mathbf{b}_{+}^{j})|\).</p>

<p style="padding-left:200px;">Consider the difference \(\Delta \equiv |(Y_{+}^{j} \setminus \{x\}, \mathbf{c}_{+}^{j})| - |(Y_{+}^{i} \setminus \{x\}, \mathbf{c}_{+}^{i})|\). Construct two new opportunity sets that are otherwise identical except for the fact that half of \(\Delta\) is added (spread out) equally to the membership grades of \(i\) and subtracted equally from the membership grades of \(j\). Call these new sets \((Y^{i}_{+} \setminus \{x\}, \mathbf{d}^{i}_{+})\) and \((Y^{j}_{+} \setminus \{x\}, \mathbf{d}^{j}_{+})\), respectively. Further, consider the equalising transformations of these latter sets: \((Y^{i}_{+} \setminus \{x\}, \mathbf{e}^{i}_{+})\) and \((Y^{j}_{+} \setminus \{x\}, \mathbf{e}^{j}_{+})\), respectively. Clearly, by construction, \(|(Y^{i}_{+} \setminus \{x\}, \mathbf{d}^{i}_{+})| = |(Y^{j}_{+} \setminus \{x\}, \mathbf{d}^{j}_{+})|\) and \(|Y^{i}_{+} \setminus \{x\}| = |Y^{j}_{+} \setminus \{x\}| = n\). Hence, by the induction hypothesis, \((Y^{i}_{+} \setminus \{x\}, \mathbf{d}^{i}_{+}) \sim (Y^{j}_{+} \setminus \{x\}, \mathbf{d}^{j}_{+})\). Further, \(|(Y^{i}_{+} \setminus \{x\}, \mathbf{e}^{i}_{+})| = |(Y^{j}_{+} \setminus \{x\}, \mathbf{e}^{j}_{+})|\) and \(|Y^{i}_{+} \setminus \{x\}| = |Y^{j}_{+} \setminus \{x\}| = n\), and hence also \((Y^{i}_{+} \setminus \{x\}, \mathbf{e}^{i}_{+}) \sim (Y^{i}_{+} \setminus \{x\}, \mathbf{e}^{i}_{+})\).</p>

<p style="padding-left:200px;">Now, consider \((Y^{i}_{+} \setminus \{x\}, \mathbf{e}^{i}_{+}), (Y^{j}_{+} \setminus \{x\}, \mathbf{e}^{j}_{+})\) and the equalising transformations of the original sets: \((Y^{i}_{+}, \mathbf{e}^{i}_{+})\) and \((Y^{j}_{+}, \mathbf{e}^{j}_{+})\). Notice that the difference between these pairs of opportunity sets is the addition of the option \(x\). And further, notice that by construction \(\mu^{i}(x) = \mu^{j}(x)\) in these opportunity sets. Hence, by INDa, we have: \((Y^{i}_{+}, \mathbf{e}^{i}_{+}) \sim (Y^{j}_{+}, \mathbf{e}^{j}_{+})\). And hence, by DI, \((Y^{i}_{+}, \mathbf{b}^{i}_{+}) \sim (Y^{j}_{+}, \mathbf{b}^{j}_{+})\).</p>

<p style="padding-left:200px;">(i.2) Suppose now that \(Y_{+}^{i}\) and \(Y_{+}^{j}\) are disjoint. The argument runs as in (i.1) except now we consider \(X^{i}_{+} \setminus \{x\}\) and \(X^{j}_{+} \setminus \{y\}\) where \(x\) is originally available to agent \(i\) but not to agent \(j\) and vice versa.</p>

<p style="padding-left:200px;">So we have shown that when two opportunity sets, \((X_{+}^{i}, \mathbf{a}_{+}^{i})\) and \((X_{+}^{j}, \mathbf{a}_{+}^{j})\), with the same cardinality are such that \(|X_{+}^{i}| = |X_{+}^{j}|\), then \((X_{+}^{i}, \mathbf{a}_{+}^{i}) \sim (X_{+}^{j}, \mathbf{a}_{+}^{j})\).</p>

<p style="padding-left:150px;">(ii) Suppose \(|X_{+}^{i}| \neq |X_{+}^{j}|\) is the case. Without loss of generality, suppose that \(|X_{+}^{i}| > |X_{+}^{j}|\). So there are some options available to \(i\) that are not available to \(j\). Take set \(A \subseteq X^{i}_{+}\) such that \(|X^{i}_{+} \setminus A| = |X^{j}_{+}|\). Consider \((X^{i}_{+} \setminus A, \mathbf{b}^{i}_{+})\) and \((X^{j}_{+}, \mathbf{a}^{j}_{+})\). By construction, it must be that \(|(X^{i}_{+} \setminus A, \mathbf{b}^{i}_{+})| < |(X^{j}_{+}, \mathbf{a}^{j}_{+})|\). Consider the difference between these cardinalities and distribute it as in (i.1). This yields the two opportunity sets, \((X^{i}_{+} \setminus A, \mathbf{c}^{i}_{+})\) and \((X^{j}_{+}, \mathbf{c}^{j}_{+})\), which have the same cardinality and hence, by step (i), \((X^{i}_{+} \setminus A, \mathbf{c}^{i}_{+}) \sim (X^{j}_{+}, \mathbf{c}^{j}_{+})\). Consider the two equalising transformations of these sets, \((X^{i}_{+} \setminus A, \mathbf{e}^{i}_{+})\) and \((X^{j}_{+}, \mathbf{e}^{j}_{+})\), which by INDa must also be indifferent. Further, consider the equalising transformation of the original opportunity set available to \(i\): \((X^{i}_{+}, \mathbf{e}^{i}_{+})\).</p>

<p style="padding-left:150px;">Now, take \((X^{i}_{+} \setminus A, \mathbf{e}^{i}_{+})\) and add an option from set \(A\) to \(X^{i}_{+} \setminus A\) and also add only half of the options membership grade to the respective vector. We thus get opportunity set \((X^{i}_{+} \setminus A \cup \{x\}, \mathbf{d}^{i}_{+})\) with its equalising transformation \((X^{i}_{+} \setminus A \cup \{x\}, \mathbf{e}^{i}_{+})\). Further, take set \((X^{j}_{+}, \mathbf{e}^{j}_{+})\) and add the same amount equally to all grades, yielding \((X^{j}_{+}, \mathbf{e*}^{j}_{+})\). By MON(1), \((X^{i}_{+} \setminus A \cup \{x\}, \mathbf{e}^{i}_{+}) \sim (X^{j}_{+}, \mathbf{e*}^{j}_{+})\).</p>

<p style="padding-left:150px;">By a series of such repetitions, we obtain indifference between the equalising transformations of the original opportunity sets: \((X^{i}_{+}, \mathbf{e}^{i}_{+}) \sim (X^{j}_{+}, \mathbf{e}^{j}_{+})\). And hence, by DI, we obtain indifference between the original opportunity sets: \((X^{i}_{+}, \mathbf{b}^{i}_{+}) \sim (X^{j}_{+}, \mathbf{b}^{j}_{+})\).</p>

<p style="padding-left:150px;">Summing up (i) and (ii), we have shown that for two opportunity sets with the same cardinality, we have: \((X^{i}_{+}, \mathbf{b}^{i}_{+}) \sim (X^{j}_{+}, \mathbf{b}^{j}_{+})\). This completes (1).</p>

<p style="padding-left:100px;">(2) Now, take two opportunity sets such that, without loss of generality, \(|(X^{i}_{+}, \mathbf{a}_{+}^{i})| > |(X^{j}_{+}, \mathbf{a}_{+}^{j})|\). By a series of arguments similar to the ones in (1), it is easy to show that \((X^{i}_{+}, \mathbf{a}_{+}^{i}) \succ (X^{j}_{+}, \mathbf{a}_{+}^{j})\). The strategy is to start with the equalising transformations of these opportunity sets and then, using transitivity, to apply MON(2) to a series of sets that build up to the one with a larger cardinality.</p>

<p style="padding-left:100px;"><u>Summing up</u></p>

<p>I believe that there are a couple of things we can learn from this exercise about the usefulness of Côté’s generalised approach. First, as already noted, Pattanaik and Xu’s original axioms have cardinality restrictions baked into them and hence the characterisation follows naturally.</p>

<p>More interestingly, however, the axioms and the steps in the proof tell us a couple of things. Cardinal measures of freedom are not only, as commonly thought, insensitive to the <cite>quality</cite> of options. They are also insensitive to the <cite>distribution</cite> of accessibility. Or, put differently, to the quality of accessibility which might be thought of as a combination of access to specific options.</p>

<p>Here is an example. Suppose that Bob, who comes from a well-off family, has two perfectly available options: going to Harvard, and Yale. Further suppose that Carol, who comes from a less well-off family, has these same options (at a lesser availability) and also some worse options but with a better availability. (Bob’s family might have ruled out ex ante any other options for Bob.) Bob’s opportunity set is \(B^{1} = (\{H, Y\}, (0.9, 0.9))\) and Carol’s is \(C^{1} = (\{H, Y, C, D\}, (0.15, 0.15, 0.8, 0.8))\). The classical and fuzzy cardinal measures agree on the freedom ranking in this case: both say that Carol is more free than Bob. But the reasons they give are different and, more importantly, I believe, our intuitions about the importance of these reasons are also different. The reason why we might find it counter-intuitive to say that Carol is more free than Bob is not <cite>simply</cite> because of the quality of the options in her set. Rather, the reason is also that Carol’s access to the better options is much worse than that of Bob’s.</p>

<p>The axioms that the generalised cardinality measure satisfy can reveal another issue: such measures are not sensitive to the <cite>distribution</cite> of access. Suppose that Carol’s opportunity set changes to \(C^{2} = (\{H, Y, C, D\}, (0.1, 0.1, 0.85, 0.85))\). In other words, her chances for Harvard and Yale have diminished but her chances for the worse options have improved. The generalised cardinality measure would still say that she is more free than Bob. Or further suppose that her set changes to \(C^{3} = (\{H, Y, C, D\}, (0.475, 0.475, 0.475, 0.475))\). She now has much better chances at getting her \(H\) and \(Y\) options and yet, by the GSCO, she is just as free as before.</p>

<p>If we want to avoid such conclusions, we need a measure that is sensitive <cite>both</cite> to the quality of options (something that the current literature already recognises) and to the distribution of access across these options. And such differential distributions stem not just from subjectivist factors, such as weakness of will, but more significantly from social factors, such as resource-based disadvantages. Côté’s approach thus allows us to bring the literature on the measurement of freedom much closer to the literature on the measurement of equality of opportunity—both in political philosophy and economics. To take just one issue that opens up here, it is not very straightforward to say what <cite>equality</cite> of freedom means in the generalised framework because trade-offs between the quality and number of options, on the one hand, and the quality of access, on the other, kick in. To the extent that plausible generalised measures can be constructed, they must propose properties that describe convincing, and justifiable, trade-offs.</p>
