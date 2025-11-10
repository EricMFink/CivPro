---
date: Fall 2021

subject: Civil Procedure
author: Professor Fink
affiliation: Elon Law School

title: Final Exam -- Model Answers & Comments

output:
  pdf_document:
    latex_engine: xelatex
    template: default.tex
    path: /assets/pdf/CivProExam2021-Answers.pdf

---

# Model Answers

## Question 1

The United Novelty & Explosive Workers Union ("Union") represents employees at Acme Corp., pursuant to the National Labor Relations Act ("NLRA", a federal statute). A collective bargaining agreement ("CBA") between the Union and Acme governs the terms and conditions of employment for Acme employees. The CBA provides that any disputes arising under the CBA must be resolved through a contractual grievance procedure, culminating in binding arbitration between the Union (representing the interests of the employee initiating the grievance) and Acme. Arbitration is the exclusive remedy for any alleged breaches of the CBA, i.e. neither the Union nor the employee may bring a civil lawsuit over such a dispute. But the grievance and arbitration procedure does not apply to claims based on federal or state statutes.

The CBA also provides that Acme may not discharge an employee without good cause. An employee who believes they have been fired without good cause may ask the Union to pursue a grievance on their behalf. The arbitrator's jurisdiction is limited to disputes based on the CBA itself. If the arbitrator finds that the employee was fired without good cause, the exclusive remedy is reinstatement with back pay.

Wilma Wolf, an Acme employee represented by the Union, was fired for allegedly falsifying her time records. Wolf denied falsifying the time records and initiated a grievance, which the Union took to arbitration. In accordance with the CBA, Wolf was suspended without pay, pending the outcome of the arbitration.

At the arbitration hearing (similar to a trial before a judge, but with more relaxed procedures and without the extensive discovery available in a civil suit), Acme and the Union introduced evidence regarding the alleged falsification of Wolf's time records. The arbitrator found that Wolf did not falsify the time records, and that there was not good cause for discharge as required under the CBA. Accordingly, the arbitrator sustained the grievance and ordered Acme to reinstate Wolf to her former position with back pay for the period of her suspension. Acme sought judicial review in federal court, which affirmed the arbitrator's decision. Under the applicable law, an arbitration decision may have claim and issue preclusive effect if it is affirmed by a court.

Wolf then filed a lawsuit against Acme in federal court, asserting an employment discrimination claim under Title VII ("FLSA", a federal statute). In her complaint, Wolf alleges that the real reason she was fired was in retaliation for complaining about sexual harassment by her supervisor at Acme (something that was not raised in the arbitration). Wolf seeks compensatory and punitive damages, as provided under the Title VII.

_Is Wolf's lawsuit barred by claim preclusion based on the arbitration decision?_

### Answer

Claim preclusion serves the goals of finality, consistency, & judicial economy by prohibiting relitigation of claims that were previously decided on the merits by a valid & final judgment between the same parties. In this case, the application of claim preclusion depends on whether the decision in the grievance arbitration is a prior judgment with preclusive effect, whether the arbitration and the civil suit involve the same parties, and whether the arbitration and the civil suit involve the same claim.

#### Valid & Final Judgment on the Merits

To have preclusive effect, the prior judgment must have been valid, final, and on the merits. A judgment is valid if the court had jurisdiction over the subject matter and parties. A judgment is final if it fully disposes of the action and there is nothing left for the court to do. A judgment is on the merits if it is based on the elements of the claims or affirmative defenses, rather than some procedural ground such as lack of jurisdiction.

In this case, the Union and Acme contractually agreed to submit all grievances arising under the CBA to arbitration, and there is nothing to suggest that the arbitrator lacked jurisdiction to decide the grievance over Wolf's firing. So the decision was presumably valid.

The arbitrator decided the grievance in favor of Wolf and ordered Acme to reinstate her with back pay. That decision fully resolved the grievance, and was thus final.

The basis for the arbitrator's decision was that Acme failed to show good cause to fire Wolf, as required under the CBA. That was decision on the merits, i.e. a determination of the parties' substantive rights and duties, rather than on procedural grounds.

Because the prior judgment was issued by an arbitrator, there is an additional requirement: it must have been affirmed by a court. That is also true in this case.

Accordingly, the prior judgment here satisfies the conditions for claim preclusion.

#### Same Parties

Claim preclusion further requires that the prior judgment was between the same parties in the same positions as in the subsequent suit. That is, in both actions, the same party must assert a claim against the same opposing party. This requirement is known as mutuality of preclusion, i.e. both parties are bound by the prior judgment. Where the claimant in the subsequent action is not identical to the claimant in the prior action, mutuality may still be satisfied if they are in privity, a contractual or other legal relationship in which they represent the same legal interest.

Here, the parties to the two actions are not strictly identical. In the civil suit, Wolf is the plaintiff and Acme the defendant. The parties to the arbitration were Acme and the Union, not Wolf herself. However, the Union acted in a representative capacity, seeking a remedy on behalf of Wolf for a breach of her rights under the contract. Accordingly, the mutuality requirement is satisfied here.

#### Same Claim

For purposes of claim preclusion, a claim includes all causes of action arising from the same transaction or occurrence. Courts generally take a pragmatic approach: rather than focusing on the source of the rights & duties at stake, the particular injuries or wrongful acts alleged, or the specific remedies sought, the question is whether there is a sufficient logical connection among the causes of action that it makes sense for them to be litigated together. For example, where a plaintiff alleges that the defendant's negligence caused a collision between the parties' cars, the plaintiff's claims for personal injury and for property damage are both part of the same claim; if the plaintiff asserts only the personal injury claim in the first suit, and that suit ends in a valid and final judgment on the merits in favor of either party, the plaintiff may not subsequently bring the property damage claim.

Here, the grievance under the CBA and the retaliation claim under Title VII both arise from the same occurrence: Acme's termination of Wolf's employment. Under the logical relationship approach, this is enough to treat the two causes of action as part of the same claim. It doesn't matter that they rest on different legal theories & rights (contractual protection against being fired without cause v. statutory protection against retaliation) or involve different facts (the Title VII claim involves facts, not relevant to the arbitration, about whether Wolf complained about harassment and whether that was the real motive for her being fired).

However, claim preclusion will bar a previously unasserted cause of action only if the claimant could have asserted that cause of action in the prior forum. In this case, the arbitrator had exclusive jurisdiction over grievances based the Union contract, but no jurisdiction over claims arising under federal statutes like Title VII. If Wolf wished to pursue both causes of action, she had no choice but to do so in separate actions before different tribunals. Moreover, even if Wolf could have asserted her retaliation claim in the arbitration, the only remedy available would have been back pay, and she would still be permitted to bring a separate action in court to seek the additional statutory remedies available under Title VII.

---

## Question 2

Regardless of your answer to the previous question, assume that Wolf's lawsuit is not barred by claim preclusion.

In its answer to Wolf's complaint, Acme denies that Wolf ever complained about sexual harassment and asserts that Wolf was fired for falsifying her time records (which, if true, would be a defense to the Title VII claim).

_Does issue preclusion apply to the issue of whether Wolf falsified her time records?_

### Answer

Issue preclusion prevents the relitigation of legal and factual issues that were conclusively decided in a prior action. Issue preclusion may be asserted offensively, i.e. by a claimant, to establish an element of a claim, or defensively, i.e. by a defending party, to defeat an element of a claim or support an affirmative defense.

As with claim preclusion, the prior judgment must have been valid and final, which have the same meaning as for claim preclusion (see answer to Question 1). But the prior judgment doesn't necessarily have to be on the merits. A judgment based on procedural grounds, such as lack of jurisdiction, may still support preclusion on any issues of fact or law on which it rests.

For issue preclusion, the issue must also have been actually litigated and essential to the prior judgment. An issue is actually litigated if the parties contest and offer evidence on the issue at trial or in a dispositive motion. Issue preclusion will not apply if the parties do not contest the issue, e.g. if the defendant admits to a factual allegation, or the parties stipulate to certain facts.

An issue is essential to the judgment if a different resolution of the issue would have resulted in a different outcome. For example, suppose A, a delivery truck driver, sues B, the company whose packages A delivers, for employment discrimination. B defends on two grounds: first, that A is an independent contractor, not an employee (and thus not covered by employment discrimination law at all), and second, that even if A was an employee, there was no discrimination. Assume the court finds that A is an employee and that B did discriminate, and enters judgment in favor of A. The court's finding that A is an employee is essential to the judgment, because if A was not an employee, B would have won. But suppose the court finds that A is an employee but that B did not discriminate, and enters judgment in favor of B. In this case, the finding that A is an employee is not essential to the judgment, because a contrary finding on that issue wouldn't change the outcome of the suit.

The mutuality requirement is relaxed for issue preclusion. The party against whom issue preclusion is asserted must have been a part, and the issue must have been decided against them, in the prior action. But the party asserting issue preclusion may be a new party. This is called non-mutual issue preclusion. Non-mutual defensive issue preclusion is generally allowed, if the party against whom preclusion is asserted had a full and fair opportunity to litigate the issue in the prior action. For non-mutual offensive issue preclusion, courts will also consider additional factors to ensure fairness:

- Whether the new party could have joined as a party to the prior action, but chose to wait and see what happened;
- Whether the stakes in the prior action were so low that the repeat party had little incentive to contest the issue fully;
- Whether the repeat party lacked important procedural opportunities in the prior forum that might have made a difference to the determination of the issue;
- Whether there were inconsistent determinations of the issue in multiple prior actions.

In _Parklane Hosiery v. Shore_, Shore, a shareholder, sued Parklane over an allegedly fraudulent proxy statement. Parklane had previously lost a suit brought by the Securities & Exchange Commission over the same issue. The Supreme Court held that Shore could assert issue preclusion to prevent Parklane from disputing that the proxy statement was materially false. The fairness factors weighed in favor of allowing non-mutual offensive issue preclusion: Shore could not have joined or intervened in the SEC suit; Parklane faced significant financial liability in the SEC suit, and should have anticipated that shareholders would follow with their own suits; both suits were in federal court, with identical procedures; and there were no prior inconsistent determinations of the issue.

#### Valid & Final Judgment

As explained in the answer to Question 1, the arbitrator had jurisdiction over the contract dispute between the parties, the arbitrator's decision fully and finally resolved that dispute, and the decision was affirmed by a federal court. Accordingly, the prior judgment was valid and final.

#### Same Issue, Actually Litigated, & Essential to Judgment

The issue of whether Wolf falsified her time records is the same in both cases. In the first case, it was the central issue, arising as the alleged basis for Acme's firing of Wolf. In the second case, it arises in the context of Acme's defense to the Title VII claim, that they fired Wolf because of the time records and not because of complaints about sexual harassment.

In the arbitration, the parties contested and offered evidence on this issue. Based on the evidence, the arbitrator found that Wolf did not falsify her time records, concluded that Acme lacked good cause to fire Wolf, and ordered her reinstatement with back pay. If the arbitrator had found to the contrary, that Wolf did falsify her time records, the result would have been a decision in favor of Acme.

Accordingly, the issue was both actually litigated and essential to the judgment in the prior action.

#### Mutuality

As previously explained (see answer to Question 1), both actions involve the same parties: Wolf (represented by the Union in the arbitration) as claimant and Acme as defendant. Consequently, there is mutuality of preclusion in this case.

Even if Wolf was a "new" party, the fairness factors would likely weigh in favor of allowing non-mutual offensive issue preclusion here. Like Shore, Wolf could not have joined as a party in the prior action; like Parklane, the stakes for Acme in the prior action (having to reinstate Wolf with back pay) were sufficient to give Acme an incentive to fully contest the issue; and there are no prior inconsistent findings on the issue. Acme's best argument would be that the limited discovery and more informal procedures in the arbitration meant they did not have a full and fair opportunity to litigate the issue. But unless they can show there was evidence they would have obtained and introduced that could have changed the outcome, it’s unlikely this would outweigh the other factors.

---

## Question 3

Carl Carpenter (a citizen of NC) enjoys furniture making as a hobby. He orders some exotic wood from Tennessee Timber (a business incorporated and based in TN) for a new project. Tennessee Timber's standard form sales contract includes the following forum selection clause:

> Any suit involving this Agreement and/or any claims or disputes relating to the agreements and transactions between the parties shall be brought in either (i) the Circuit Court of Knox County in the State of Tennessee or (ii) the U.S. District Court for the Eastern District of Tennessee, and the buyer hereby submits to the jurisdiction and venue of that Court.

When the shipment arrived at his home, Carl was horrified to discover that the wood was infested with termites. He was even more horrified when the termites spread through his home, causing $100,000 worth of damage.

Carl files suit against Tennessee Timber in the U.S. District Court for the Middle District of North Carolina, asserting claims for breach of contract and breach of warranty under state law (assume that the federal court has jurisdiction based on diversity of citizenship and do not discuss that issue). Tennessee Timber moves for a change of venue to the Eastern District of Tennessee, based on the forum selection clause in the sales contract. Carl opposes the motion, arguing that the forum selection clause is unenforceable under state law.

The standard for determining whether a contractual choice of forum clause in a consumer contract is different under state and federal law. In this case, if state law applies, the forum selection clause would likely be held unenforceable and the court would thus deny the motion for a change of venue. But if federal law applies, the clause will almost certainly be held enforceable and the court would thus grant the motion for a change of venue.

_Should the court apply state or federal law in deciding whether to enforce the forum selection clause?_

### Answer

Two federal statutes, the Rules of Decision Act (RDA) and the Rules Enabling Act (REA) govern the choice between state and federal law in federal court. The Supreme Court has developed different analytical approaches, depending on which of these statutes controls the choice.

#### RDA/Erie Approach

The RDA provides that "The laws of the several states, except where the Constitution or treaties of the United States or Acts of Congress otherwise require or provide, shall be regarded as rules of decision in civil actions in the courts of the United States, in cases where they apply." In Erie R.R. v. Tompkins, the Supreme Court held that federal courts must follow state law, whether common law or statue, in suits raising state claims (i.e. under diversity or supplemental jurisdiction).

The aim of the Erie doctrine is uniform enforcement of state-created rights and obligations. If federal and state courts applied different rules yielding different outcomes in otherwise similar cases, it would encourage forum shopping for the most favorable rules. This would result in the inequitable administration of the laws: People couldn't be sure what legal rules apply to their activity until after they end up in court; but, because of the limits on diversity jurisdiction, only some parties would be able to take advantage of more favorable rules by litigating in federal court. Applying the same rules in federal and state court avoids this problem.

The RDA's mandate only applies to substantive rules, i.e. those defining the rights, duties, liabilities, and available remedies under state law. It does not require that federal courts follow state procedures. Parties might still engage in forum shopping for more convenient or otherwise preferable procedures. But this doesn't raise the same concern about inequity resulting from inconsistent enforcement of state-created rights and obligations.

In cases following Erie, the Court has developed an approach to classifying rules as substantive or procedural, rooted in the policy of achieving uniform enforcement of state-created rights. If applying different rules in federal and state court would promote forum shopping for more favorable outcomes and produce an inequitable administration of state laws, the rules will be regarded as substantive and a federal court must follow the state rule. But if the difference in the rules will not determine the outcome of the suit, or at least not strongly and predictably so, the rules will be regarded as procedural and the RDA will not control the choice. In this situation, federal courts may follow federal procedure, particularly where doing so furthers an important federal policy interest.

Byrd v. Blue Ridge Elec. Coop illustrates the analysis. Byrd sued for injuries he sustained while working for one of Blue Ridge's contractors. Blue Ridge moved to dismiss, arguing that Byrd was a statutory employee of Blue Ridge under state workers' compensation law (thus barred from bringing a civil suit for his on-the-job injury). The issue was who should decide Byrd's employee status: the judge, as state law provided, or a jury, as was the practice under federal law. Either way, the same standard would apply to the question of whether Byrd was a statutory employee (a substantive matter on which the RDA mandated that state law applied). Even though juries and judges might reach different conclusions in the run of cases, the choice between judge and jury would not predictably determine the outcome in a given case. Concluding that the RDA did not compel the federal court to follow state law, the Court concluded that the countervailing federal policy interest in favor of the right to a jury tipped the scales in favor of following the federal practice.

#### REA/Hanna Approach

A different standard applies where the federal rule at stake comes from the FRCP. The REA declares that rules adopted in accordance with that statute--which includes the FRCP--have precedence over any conflicting rules. In Hanna v. Plumer, the Court held that the RDA/Erie analysis does not apply to a choice between state law and the FRCP. Instead, if there is a direct conflict between the two, then a federal court must follow the FRCP rule, as long as it is valid under the REA.

A direct conflict exists where it is not possible to comply with both rules, or where there FRCP rule is more permissive than state law. For example, in Hanna, the plaintiff served the complaint and summons by leaving copies with the defendant's wife at their home, as permitted under the FRCP. State law specifically required personal service on the defendant. Even though this was also a valid method of service under the FRCP, the Court held that the more permissive FRCP rule applied.

A rule is valid under the REA if it was adopted in accordance with the statutory procedure and does "not abridge, enlarge or modify any substantive right." The inquiry here is whether the federal rule really regulates procedure, i.e. the judicial process for hearing and deciding disputes over rights and duties created under substantive law. As long as a rule is rationally capable of classification as procedural, it will be considered valid under the REA, even if it may have some effect on outcomes. In practice, no FRCP rule has ever been held invalid under this test.

#### RDA/Erie Analysis

This question involves a choice between state and federal law on the enforceability of a contractual choice of forum clause. The federal rule here is not part of the FRCP, and there is no indication that it is from a federal statute (in which case the analysis would be similar to Hanna). Assuming it is a judge-made rule, the RDA/Erie analysis applies.

The difference between state and federal law here is not outcome determinative in the relevant sense under Erie. Of course, the choice will likely determine the outcome on the issue of whether the forum selection clause is enforceable, and thus whether a change of venue from NC to TN is granted. But the question under the RDA/Erie analysis is whether the choice of federal or state law would determine the ultimate outcome of the suit. In this case, it would not.

The situation here is similar to Byrd. There, the issue was whether the judge or a jury should decide whether the plaintiff was the defendant's statutory employee under state law. Here, the issue is whether a NC or TN court should decide whether the defendant is liable for breach of contract and warranty. While each party likely perceives some advantages to litigating in their home state, such as greater convenience and a more sympathetic judge or jury, it is far from certain that the choice of forum will determine who wins the suit. As in Byrd, in either court, state law will apply to the underlying substantive question of whether the defendant is liable for breach of contract and warranty. (There might be a disagreement over which state's law, NC or TN, applies; but that is a separate question not raised here.)

Consequently, the RDA/Erie policy of ensuring the uniform enforcement of state-created rights and obligations is not not stake here. As in Byrd, the choice of law is relatively unconstrained by the RDA. The federal court may follow the federal rule, particularly if it advances some important federal policy interest (e.g. favoring the freedom and enforcement of contacts). Or, if the court determines that there is no strong countervailing federal policy interest, but that the state rule furthers some important state policy interest (e.g. protecting consumers from overreaching by businesses), it may opt to adopt the state rule for the sake of consistency.

#### REA/Hanna Analysis

If the federal rule here was from a federal statute, the analysis would be similar to Hanna:

The first question would be whether there is a direct conflict between the federal and state rule. Under state law, the forum selection clause will be unenforceable, while under federal law, it will be enforceable. The rules are thus in direct conflict.

The next question would be whether the statute establishing the federal rule was a valid exercise of legislative power under the constitution. Assuming Congress has the constitutional authority (for example, under the contracts or commerce clause) to adopt a statute on the enforceability of contractual choices of forum, the statute will be valid and controlling by virtue of the supremacy clause.

\newpage

# Comments

## Questions 1 & 2: Preclusion

There was some confusion about the parties and their positions:

- In the first action (contract grievance arbitration), the "plaintiff" was the Union and the "defendant" was Acme (the employer).[^1] Technically, Wolf herself was not a party; the Union represents her interest (somewhat like a guardian ad litem); since this wouldn't be obvious to someone unfamiliar with labor arbitration, I gave credit for otherwise correct answers that assumed Wolf was the "plaintiff" (or a "co-plaintiff" along with the Union) in the arbitration.
- In the second action (Title VII suit), the plaintiff is Wolf herself, and the defendant is Acme. In this case, the Union is not a party (since it only represents Wolf's interest in matters arising under the collective bargaining agreement).

There also appears to have been some confusion as to which party would raise claim or issue preclusion in the Title VII suit.

- Acme, the defendant in the Title VII suit, would raise claim preclusion, asserting that Wolf's Title VII claim should be dismissed based on the prior judgment in the arbitration case.
- Wolf, the plaintiff in the Title VII suit, would raise issue preclusion, asserting that the issue of whether she falsified her time records was conclusively decided against Acme in the arbitration case.

## Question 1: Claim Preclusion

##### 1. Prior Judgment: Valid, Final, On the Merits

Some answers neglected to define, or incorrectly defined, these key terms.

Some answers conflated "on the merits" with the "actually litigated" requirement for issue preclusion.

##### 2. Scope of Preclusion

Some answers confused claim preclusion with compulsory counterclaims.

- In this problem, Wolf was not a defendant in either case. So she wouldn't have asserted any counterclaims at all.
- Also, the FRCP wouldn't apply in an arbitration, though some arbitration rules may have similar counterclaim provisions.
- Claim preclusion and Rule 13(a) do share the same standard for which claims are barred: all claims arising from the same T/O. So I gave credit for a correct analysis under this standard, even if the answer incorrectly cited Rule 13(a) as the applicable rule.

Some answers conflated the "same T/O" standard with the issue of whether a claim "could have been asserted" in the prior action. These are two discrete issues.

##### 3. Same Parties in Same Positions

Confusion over the parties and their positions (see comment above) led to some errors on this issue.

## Question 2: Issue Preclusion

##### 1. Valid & Final Judgement

Some answers overlooked this requirement.

- Since this part of the rule and analysis are the same as in Question 1, it was sufficient to refer back to that part of your previous answer without reiterating it in full.

Some answers incorrectly stated that the prior judgment must be on the merits for issue preclusion to apply.

##### 2. Same Issue

There was some confusion over the issue that would be subject to preclusion.

The _ultimate_ legal issue in the Title VII suit is whether Acme fired Wolf in retaliation for complaining about sexual harassment. That issue will turn on (among other things) the factual issue of whether Wolf complained about sexual harassment. These issues were not raised at all in the arbitration.

But issue preclusion applies to _any issue_ that was conclusively decided in the prior case, not just the ultimate issue. Because the issue of whether Wolf falsified her time records was conclusively decided in the arbitration case, Acme may be precluded from contesting that issue again in the Title VII suit.[^2]

##### 3. Actually Litigated and Essential to Judgment

Some answers overlooked one of both of these requirements, or conflated the two.

##### 4. Mutuality

Several answers overlooked or incompletely discussed mutuality and the possibility of non-mutuality issued precision.

- Since the analysis for "same parties" is the same as in Question 1, it was sufficient to refer back to that part of your previous answer without reiterating it in full.

This question doesn't involve non-mutual issue preclusion. But I gave credit for coherently discussing and applying the standard for non-mutual issue offensive issue preclusion.

## Question 3: Choice of Law

##### 1. The RDA/Erie & REA/Hanna Tracks

The question doesn't identify the source of the federal rule about validity of a contractual forum selection clause. It certainly isn't from the FRCP. If it was from a federal statue, the analysis would be similar to Hanna.

- I gave credit for coherently analyzing of the problem under Hanna, instead of or in addition to Erie.

Some answers mistakenly treated the problem as a conflict between state law and the federal venue statutes.

- The issue at stake is not the standard for granting a transfer of venue (something we did not cover in the course), but rather the standard for whether to enforce a forum selection clause in a consumer contract.
  - Transfers of venue in federal court are governed by federal statute.
  - A valid contractual forum selection clause is one basis for granting a transfer of venue.
  - But the federal venue statues don't address the validity of such clauses.

##### 2. Erie Analysis

Some answers misapplied the outcome determinative/twin aims test.

The Erie issue only comes up when the choice between federal and state rules will determine the outcome on the _immediate_ issue those rules govern. In Byrd, for example, the choice of which rule to follow determined the issue of whether the judge or jury would decide if Byrd was an employee of Blue Ridge. But the question under Erie is whether the choice of federal or state law will determine the outcome of the suit itself, i.e. which party wins.

In this question, the choice of federal or state law will determine whether the forum selection clause is enforceable, and thus whether the court grants a transfer of venue. But that won't determine the outcome of the suit, which will be decided under state law regardless of whether the case remains in the NC federal court or is transferred to the TN federal court.

[^1]: Note that the terms plaintiff and defendant aren't actually used in labor arbitration; but the concept is the same.

[^2]: Strictly speaking, under Title VII, Acme would not necessarily have to prove that Wolf _really_ falsified her time records, but only that they fired Wolf because they _believed_ she had done so. But the issue of whether she really did so may be relevant to determining whether Acme genuinely believed she did.
