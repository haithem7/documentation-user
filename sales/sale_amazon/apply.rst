================================
Apply for Amazon MWS Access Keys
================================

.. _amazon/developer-form:

Submit the Amazon MWS Developer Registration and Assessment Form
================================================================

In order to synchronize your Amazon orders with Odoo, Amazon MWS access keys are required.
They can be obtained by submitting the **Amazon MWS Developer Registration and Assessment form** to
register as a developer. Once recognized by Amazon as a developer (i.e. you make use of an
application connecting to MWS), you will be granted Amazon MWS access keys.

First, visit the `Amazon Marketplace Web Service documentation
<http://docs.developer.amazonservices.com/en_US/dev_guide/DG_Registering.html>`_ and follow the
instructions to register as a developer. Take care to choose the form "I represent a seller
organization integrating with Amazon MWS for its own selling account only.".

Fill out the *Developer Registration and Assessment form* as suggested below and provide your own
contact information in the **Developer contact information** section. In the **Business use
information** section, select the correct region of your seller account. For the other sections,
take care to adapt your responses in accordance with your business case. Give a particular attention
to the **Merchant Fulfilled Shipping** function that should only be checked if you ship your
products yourself. You should uncheck it if you sell exclusively with the *Fulfillment by Amazon*
service.

.. warning ::
   If you check the **Merchant Fulfilled Shipping** function (i.e. you request access to Personally
   Identifiable Information (PII) of your customers), Amazon may request you to fill out a second
   form before granting you MWS access keys. As the form depends on the data protection policy of
   the region of your seller account (e.g. GDPR in Europe), we cannot provide you with a pre-filled
   form. Instead, the answers of questions related to Odoo are listed in the `Answer the Additional
   Form`_ section. Please note that this is not recommended if you use *Odoo Online* or *Odoo.sh* as
   the additional security requirements asked by Amazon may not be met by Odoo.

.. image:: ./media/dev_form.png

Answer the Additional Form
==========================

This section lists all questions asked by Amazon in additional forms so far. The answers are
tailored for *Odoo Online* and *Odoo.sh*. If you host your Odoo instances yourself (*on-premise*),
you may need to adapt some answers to your own infrastructure and data protection policy.


- **Describe all functionalities in your application where Personally Identifiable Information (e.g.
  customer name, street address, billing address) is required.**

  TODO

- **List all outside parties with whom your organization shares Amazon Information (e.g. information
  exposed by Amazon through Amazon MWS, Seller Central, or Amazon's public-facing websites) and
  describe how your organization shares this information.**

  TODO

- **List all non-Amazon MWS sources where you retrieve Amazon Information.**

  TODO

- **Describe how your organization restricts public access to databases, file servers, and
  desktop/developer endpoints.**

  TODO

- **Describe how your organization uniquely identifies employees and restricts access to Amazon
  Information on a need-to-know basis.**

  TODO

- **Describe how your organization prevents Amazon Information from being accessed from employee
  personal devices.**

  TODO

- **Provide details on your organization's privacy and data handling policies (a link to your policy
  is also acceptable).**

  TODO

- **Describe where your organization stores Amazon Information and provide details on how you
  encrypt this information (e.g., algorithm).**

  TODO

- **Describe how your organization backups or archives Amazon Information and provide details on how
  you encrypt this information (e.g., algorithm).**

  TODO

- **Describe where your organization monitors and detects malicious activity in your application(s).**

  TODO

- **Describe how your organization's incident response plan addresses database hacks, unauthorized
  access, and data leaks (a link to your policy is also acceptable).**

  TODO
