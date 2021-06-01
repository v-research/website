---
layout: default
---

<div class="row b-cont-margin" style="display:grid">
    <h3 class="w-100"> A Plan for a Business, a Business for a Plan! </h3>
       <p>
        The <b style="color:#b5e853">mission</b> of V-Research is to provide the industry with the proper tools to support
        the engineering process of cyber-physical systems (CPS, a.k.a. Operational Technology), favoring the security-by-design approach
        (as mandated by many standards in most, if not all, the fields of CPS engineering, such as the DO-326A, IEC 62443, ISO 270001, J3061 and many others). 
        We proudly embrace the open-source and open-access paradigms.
    </p>

    <p>
        The Business Plan of V-Research is articulated over 3 pillars:
    </p>

    <br>

    <ul>
	<li><b>Consultancy</b></li>
	<li><b>Research</b></li>
	<li><b>Education</b></li>
    </ul>


    <p>
		The <b style="color:#b5e853">first pillar is consultancy</b>,
		mainly focusing on complement the customers' internal resources providing
		providing support from problem statement definition to the engineering and
		(TRL) maturation plan. We provide review of state-of-the-art
		commercial products (or academic/prototype solutions whenever commercial products are not
		available or don't fit customer needs). We support the customer in platform
		evaluation and selection, standards and regulations conformance or compliance
		testing, RFP/tender consultancy, and partnership and security assurance.
		A detailed offering is available on the <a href="solutions.html">solution webpage</a>.
    </p>
    <p>
		The <b style="color:#b5e853">second pillar is research</b>, in the field of theoretical computer science for the identification
		of an abstract theory on cybersecurity (i.e. a theory to predict insecurities in an
		abstract representation of a system, such as graphs or UML/SysML diagrams).
		This foundational research will be financially sustained by research grants (such as the <a target="_blank" href="https://erc.europa.eu/funding/starting-grants">ERC-2021-STD</a>)
		and by investing part of the revenue in internal research.
    </p>
    <p>
		The <b style="color:#b5e853">third pillar is education</b> and we offer private courses on compter science, system engineering, and our beloved cybersecurity. 
		Some of our courses and seminars are available from <a href="https://edu.v-research.it">edu.v-research.it</a> and <a href="https://www.thepracticalmen.com">the-practical-men</a>.
    </p>
</div>


<div class="row b-cont-margin">
	<h3 class="w-100"> EU Funding</h3>
	<p>
		We are submitting a proposal for the ERC-2021-STD call.  We cannot disclose yet
		our project plan and project description but we are asking for 1.3M
		eur for a 4 years project with a team of 5.
	</p>
</div>

<div class="row b-cont-margin">

	<h3 class="w-100"> Products and Long-term Vision</h3>
	<p>
		With research funding (both the EU projects and the internal
		research for the global purple challenge) aim at producing a TRL 5 tool-chain
		for the secure engineering of cyber-physical systems.  Once the tool-chain is
		ready (currently the project plan is sized on the EU proposal discussed above
		and takes 4 years but we are working to shrink it to 2 years), V-Research will adopt the open-core model and develop
		services around the open-source tool-chain. For example, the current prototype
		is a security risk assessment tool.  Dedicated libraries for the risk
		assessment in specific domains (e.g. automotive, aerospace) will be offered
		upon payment for the commercial use.
	</p>
</div>

<div class="row b-cont-margin">
	<h3 class="w-100"> Global Purple Challenge</h3>
	<p>
		Our mission is to develop a scientific theory of cybersecurity and a toolchain
		for the secure engineering of cyber-physical systems. Cybersecurity is still a
		relatively new research field and
		<a href="https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/herley">lacks of foundational understanding</a>
		to make current products suitable for the engineering of secure systems. 
	</p>

	<p>
		As is common knowledge, the majority of the reported (system/users) misbehavior 
		are due to ignorance or unfortunate
		events. Mis-behaviors seem, nonetheless, un-avoidable as long as
		we do not address the problem from an engineering/design standpoint.
		So, <b>why is it so difficult to design (and then properly engineer) a system secure?</b>
		Because we simply cannot, or this is the current belief.
		Take, for example, the easiest, smallest possible system
		which implements a "function/program such that given 2 inputs,
		the output is the concatenation of them". 
	</p>
	<p>
		Let us pause here for a moment. An engineer would notice that I introduced the concatenation (running example)
		by describing its behavior, by prescribing a functional requirement (dogmatically/axiomatically).
		And so does the engineering process, it starts from some requirements.
		Suppose that our system is implemented in software (in hardware a similar reasoning applies too). 
		The software takes the first input and stores it in X 
		(i |-> X, see <a href="https://ropas.snu.ac.kr/~kwang/520/readings/sco70.pdf">[Dana Scott, Outline of a Mathematical Theory of Computation - 1970]</a>) and the second in Y.
		And then the software stores the content of the two inputs in the 
		output O, a (memory) location with twice the size of X and Y, where
		X and Y have the same size (i.e. |O|=|X|+|Y| and |X|=|Y|).
		What if O is implemented, by mistake, such that the size |O|<|X|+|Y|? (or different in general).
		That is a weakness and may cause a security issue. And how many other examplese can we think of?
		Well, as many as we can (pen)test.
	</p>
	<p>
		But let's dig deeper. The requirements on the size of the locations do not seem to
		easily follow from the initial requirements (the software just needed to concatenate). Obviously, we cannot 
		detail the requirements. Otherwise, how much do we want to detail them? Do we want to start from the definition of the mathematical grounds of
		the design of the system? 
	</p>
	<p> 	So, can we identify those mis-behaviors (and
		weaknesses) without asking an engineer for an implausible definition of all the
		security requirements of a system?
	</p>

	<p>
		The gentle introduction of our first steps are on <a href="https://www.knowledgezero.com">knowledgezero.com</a>,
		an initiative to disseminate our research and prototypes.
		Our first open-access white paper and open-source prototype
		for the cybersecurity risk assessment of systems (modeled
		in UML) are available <a href="https://github.com/v-research/cybersecurity">here</a>.
	</p>
</div>
