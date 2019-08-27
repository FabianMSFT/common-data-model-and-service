---
title: overview - Common Data Model | Microsoft Docs
description: nonProfit is a folder that contains standard entities related to the Common Data Model.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# nonProfit


## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or a potential customer. The company that's billed in business transactions.  |
|[Address](Address.md)|Address and shipping information. Used to store additional addresses for an account or a contact.  |
|[Award](Award.md)|An Award represents the total amount of funding that has been agreed to be awarded to an individual or institution.  |
|[AwardVersion](AwardVersion.md)|An Award Version represents a point in time snapshot of the attributes of an Award.  |
|[Budget](Budget.md)|A Budget represents the amount of funds that can be awarded for a particular delivery framework (i.e Program, Project, Initiative, Activity) for a defined period of time (i.e. fiscal year).  |
|[Campaign](Campaign.md)|Container for campaign activities and responses, sales literature, products, and lists to create, plan, execute, and track the results of a specific marketing campaign through its life.  |
|[Condition](Condition.md)|Specific terms and conditions attached to the Delivery Framework that, if not met, may influence the delivery of commitments made by participating organizations.  |
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as a customer, a supplier, or a colleague.  |
|[CreditPlan](CreditPlan.md)|Credit Plans control who will be credited with hard or soft credits after a payment clears.  |
|[CreditPlanRecipient](CreditPlanRecipient.md)|The contact, donor or constituent who receives "credit" for the hard or soft cleared payment.  |
|[CreditRecipient](CreditRecipient.md)|The contact, donor, or constituent who receives "credit" for the hard or soft cleared payment. A credit plan is always tied to a recipient in order to ensure full reconciliation and accounting of donations. All nonprofits have business rules that govern how hard and soft credits are applied, but these rules are notoriously inconsistent from organization to organization. For example, we recently surveyed 12 enterprise nonprofits about how they handle third-party (corporate) giving crediting. Of those organizations, half of them soft credit the corporation and hard credit the individual donors, and the other half hard credit the third-party organization that provides the matching gift payments. (For example, Benevity is a third-party gift-management company.) Still other organizations hard credit the corporations themselves. For example, Jane Smith works at Microsoft and donates $50 through that company. Microsoft matches the gift dollar for dollar, but Benevity collects and distributes the gift to Oxfam International. Where is hard and soft credit applied? Some organizations hard credit Jane Smith $100 ($50 donated plus the $50 match). Other organizations hard credit Jane Smith $50 and Microsoft $50. Some organizations hard credit Microsoft $100. Still more organizations hard credit Benevity some or all of the $100 donation.  |
|[DeliveryFramework](DeliveryFramework.md)|Delivery Framework represents a management unit of work defined by the organization or entity doing the work. In IATI, the Delivery Framework is an 'Activity.'  |
|[DeliveryFrameworkContact](DeliveryFrameworkContact.md)|Contact information for the Delivery Framework.  |
|[DeliveryFrameworkDescription](DeliveryFrameworkDescription.md)|A longer, human-readable description containing a meaningful description of the delivery framework  |
|[DesignatedCredit](DesignatedCredit.md)|A segment of a donation payment or in-kind gift that indicates the partial amount that is hard- or soft-credited to a Customer and allocated to one Designation.  |
|[Designation](Designation.md)|An area to which funds may be allocated, including a GL-relevant accounting code.  Designations are the way a donor instructs an organization about how their donation should be spent or earmarked.  |
|[DesignationPlan](DesignationPlan.md)|A line item attached to a Pledge, Payment Schedule, or Campaign indicating how associated payments should be designated.  |
|[Dimension](Dimension.md)|A category used for dis-aggregating the result by gender, age, etc  |
|[Disbursement](Disbursement.md)|A Disbursement represents an Award disbursement to an individual or organizational awardee.  A Disbursement is related to a specific Award and Budget.  |
|[DisbursementDistribution](DisbursementDistribution.md)|Disbursement Distribution represents the Framework(s) - i.e. Program, Project, Initiative - that contribute to funding an Award Disbursement.  |
|[Docket](Docket.md)|A Docket is used to group inquiries (LOIs) and/or requests with a specific grant/award cycle or date (usually a review/board meeting).  |
|[DocumentCategory](DocumentCategory.md)|IATI Document Category.  |
|[DocumentCountry](DocumentCountry.md)|The recipient country that is the focus of the document.  |
|[DocumentLanguage](DocumentLanguage.md)|The language in which target document is written.  |
|[DocumentLink](DocumentLink.md)|A link to an online, publicly accessible web page or document.  |
|[DonorCommitment](DonorCommitment.md)|Donor commitments represent the actual or prospective agreement between a donor and an organization for the donor to make a gift to the organization.  |
|[Education](Education.md)|Education references biographical information about the educational institutions a contact attended or is attending.  |
|[EmploymentHistory](EmploymentHistory.md)|Employment History represents historical and/or current information about where a contact works, volunteers or serves in some capacity at an organization.  |
|[Expenditure](Expenditure.md)|An Expenditure represents an amount of money spent by an Organization or Delivery Framework.  |
|[HumanitarianScope](HumanitarianScope.md)|Classification of emergencies, appeals and other humanitarian events and actions.  |
|[Identifier](Identifier.md)|An IATI's globally unique identifier for the delivery framework  |
|[Indicator](Indicator.md)|An Indicator describes what will be measured to track evidence of a Result. Indicators can be qualitative or quantitative and may or may not be aggregable.  |
|[IndicatorReference](IndicatorReference.md)|A standardised means of identifying the indicator from a code in a recognised vocabulary.  |
|[IndicatorValue](IndicatorValue.md)|An Indicator Value is a quantitative or qualitative value of measurement of an Indicator. Indicator Values may be but are not limited to baseline, target or actual values of measurement.  |
|[IndicatorValueLocation](IndicatorValueLocation.md)|Indicates the location of the indicator value  |
|[Lead](Lead.md)|A prospect or a potential sales opportunity. Leads are converted into accounts, contacts, or opportunities when they're qualified. Otherwise, they're deleted or archived.  |
|[Location](Location.md)|The sub-national geographical identification of the target locations of an activity. These can be described by gazetteer reference, coordinates, administrative areas or a textual description.  |
|[Membership](Membership.md)|Representation of a Customer Membership.  |
|[MembershipCategory](MembershipCategory.md)|Represents the types of membership associated to products.  |
|[NarrativeTranslation](NarrativeTranslation.md)|Allows the translation of different narrative elements for IATI reporting.  |
|[NonEmbeddedCodelist](NonEmbeddedCodelist.md)|Non-functional codelists that usually provide lookup information on e.g. currencies, languages in use, countries, etc.  |
|[NonEmbeddedCodelistVocabulary](NonEmbeddedCodelistVocabulary.md)|Sources for non embedded codelists  |
|[Objective](Objective.md)|An Objective represents the organization's highest priorities, strategies and/or goals that guide investments (in the case of Requests and Awards) and program delivery.  |
|[OfacMatch](OfacMatch.md)|OFAC Match is a placeholder entity for tracking Office of Foreign Assets Control (OFAC) Specially Designated Naturals (SDN) searches and results.  |
|[Opportunity](Opportunity.md)|Potential revenue-generating event or a sale to an account, which must be tracked through a sales process to completion.  |
|[ParticipatingOrganization](ParticipatingOrganization.md)|Organization involved with the delivery framework  |
|[PaymentAsset](PaymentAsset.md)|Payment Asset represents the assets associated with specific types of payments including, but not limited to, in-kind gifts, stocks and securities.  |
|[PaymentMethod](PaymentMethod.md)|Payment Method is a placeholder entity for customizations that may be supported by an application.  |
|[PaymentProcessor](PaymentProcessor.md)|This is a placeholder entity referenced by the Payment Method object.  It is intended to be customized with configuration data necessary to connect to a payment processor and authorize payments.  |
|[PaymentSchedule](PaymentSchedule.md)|A gift transaction can be a one-time payment or a recurring payment (ie, monthly/sustainer giving). In addition, it can be a pledge (ie, promise) of a future payment or a current/received payment.  |
|[PlannedGiving](PlannedGiving.md)|A planned gift is a gift made during a donor's lifetime or at the time of their death that involves their estate and/or tax planning.  |
|[PolicyMaker](PolicyMaker.md)|A policy or theme addressed by the Delivery Framework.  |
|[PolicyMarker](PolicyMarker.md)|A policy or theme addressed by the Delivery Framework.  |
|[Preference](Preference.md)|Preference represents an abundance of constituent or organization information that doesn't live cleanly on an account or contact record, or that can be associated with both an Account and a Contact.  |
|[RecipientCountry](RecipientCountry.md)|The country that will benefit from this delivery framework  |
|[RecipientRegion](RecipientRegion.md)|A supranational geopolitical region that will benefit from the delivery framework  |
|[Recommendation](Recommendation.md)|This is the mechanism through which Foundations provide recommendations back to a grant applicant.  |
|[Report](Report.md)|Reports represent information submitted by an awardee to the awarding entity (i.e., a Foundation) or information submitted by an authorized awarding entity individual/entity about an awardee.  |
|[Request](Request.md)|Requests represent a request from an individual or institution for funding or support. A request is more formal than an inquiry (LOI) and typically happens after an inquiry has already occurred.  |
|[Result](Result.md)|A Result is a container that represents the changes in the context in which an organization operates.  |
|[ResultReference](ResultReference.md)|A reference element to allow for the coded identification of a results framework.  |
|[Review](Review.md)|The assessment of a Request made by an internal staff member (or team) or an external third party individual or entity (i.e. Consultant) and all of the relevant information that needs to be tracked.  |
|[Salutation](Salutation.md)|A Salutation represents the way a constituent wishes to be addressed, depending on the source, purpose and content of a of communication.  Salutations may or may not be auto-created by workflow.  |
|[Sector](Sector.md)|Classification of the purpose of the Delivery Framework.  |
|[Tag](Tag.md)|Categorizations from established taxonomies that enrich the classification of the Delivery Framework but that, unlike those reported in the sector element, cannot be associated with percentage splits.  |
|[Transaction](Transaction.md)|Transactions (also referred to as donations) represent payments from a constituent (i.e. donor, contact, account or organization) to the nonprofit.  |
|[Website](Website.md)|A web address.  |
