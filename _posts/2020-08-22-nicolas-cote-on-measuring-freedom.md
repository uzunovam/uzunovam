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
