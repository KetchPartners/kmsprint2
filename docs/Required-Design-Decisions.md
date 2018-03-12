---
layout: default
title: 'Required Decisions: CRM Opportunities'
comments: true
# other options
---

# Required Design Decisions
## CRM Opportunities

### Definitions
<dl>
  <dt>Opportunity</dt>
  <dd>
    <p>An oppporunity is setup in the CRM Hybris system.</p>
  </dd>
  <dd>Opportunity is created to trigger follow-up for potential sales</dd>
  <dd>An opportunity can be created for potential sale of project</dd>
</dl>
<dl>

  <dt>Workflow</dt>
  <dd>
    <p>A business condition that is met or event that triggers the system to perform an action or series of actions.</p>
  </dd>
  <dd>Next generation workflows are built based on Fiori / Open Source web technology, rather than built with ABAP</dd>
  <dd>These workflows are mapped out using an open source tool called BPMN.  [Further information can be found at BPMN.io](https://bpmn.io)</dd>
</dl>

  <dt>Business Partner</dt>
  <dd>
    <p>An SAP term that defines a set or group of people that have a common role</p>
  </dd>
  <dd>Busines Partners are defined by type.</dd>
  <dd>Examples are project manager, sales clerk, sales account manager</dd>
</dl>

  <dt>KPI Metrics</dt>
  <dd>
    <p>CPM uses KPI metrics as a method to post planning transactional data.</p>
  </dd>
  <dd>Examples of KPI's are total revenue, total costs, quarter revenue, annual revenue etc</dd>
</dl>


*[HTML]: Hyper Text Markup Language


### Questions
- [] Process flow of opportunity management.
- [] Field or status that is set in Opportunity to trigger workflow (message wf).  
- [] The project type field in Opportunity - What are the project types? what are the field rules?
- [] The opportunity business partners that are project related?  Which partner type will trigger the CPM process?
- [] Do all opportunities require estimates? 
- [] Describe the types of estimates that would be required?
- [] What information is needed to do the estimate, that is known at the time the opportunity is created?  Is that information stored on the opportunity?  Somewhere else?
- [] Is a probability of success determined in the opportunity?  Should this probability score be used in CPM to determine what is estimated and the degree of estimation?
- [] Does the opportunity have estimated revenue and planned costs values?
- [] Is there a scope document with the opportunity?
- [] Can there be variants to the opportunity that would result in multiple estimates needed in CPM?
- [] List anything that you believe to be relevant for doing the estimate in CPM?
- [] Are planned or customer exepcted dates maintained in opportunity.
- [] What KPI estimate values are needed to be passed back to the opportunity from the project estimate?  For each required KPI, identify if total, or period based.
- [] Are documents stored in the opportunity that should be made available to the project role that does the estimate?  If so, what document management system is used, and is it integrated into CRM.
- [] Do some opportunities contain confidential information that needs a restricted audience?  If so, describe the requirement.
- [] If an opportunity does not become a contract or order, what is the close out process?
- [] Are other systems involved with opportunity management?  Where do you do your project estimates today?


