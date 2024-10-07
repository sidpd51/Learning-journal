## WhatsApp message types and 24 hour session rule
- Template messages: The messages that we get from agents in our what's regarding order or something like that. These are basically transactional messages, such as delivery alerts and appointment reminders, sent to users who have opted in to receive messages from your organization.
- Session messages: incoming messages from a customer or outgoing replies by agent. A messaging session starts when agent receive a messsage from customer and last for 24 hours from the most recently received mmesage. Session messages don't need to follow a template, and can include media attachments.

- 24 horus session rule: same as 2nd point add ons are - the agent has 24 hours to reply from the time the agent received it. However, after 24 hours, the agent can send a message to customer only by using a predefined and approved template.

## End-to-end walkthrough
- Fetch Twilio account details
- Create a WhatsApp channel
- Create routing rules
- Modify settings for a specific WhatsApp phone number