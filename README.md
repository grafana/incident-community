<img width='128' src='https://user-images.githubusercontent.com/101659/189375238-c2ab168e-f698-4f0a-84f1-41fdfa27d92d.png' />

# Welcome to the Grafana Incident Community

Grafana Incident takes away the toil, letting your teams focus on what's important when things go wrong.

## Feedback

* [Issues](https://github.com/grafana/incident-app/issues) for bug reports
* [Discussions](https://github.com/grafana/incident-app/discussions) for new feature ideas, questions, or comments

---

![Screenshot of Grafana Incident tool](https://user-images.githubusercontent.com/101659/189375059-57bb4daa-687f-4ac7-8e12-16c070ea8f65.png)

## Features

Declaring an incident is easy. You can do it in the web UI, or right from the chat.

<img width='500' src='https://user-images.githubusercontent.com/101659/189377992-32019b69-1316-4862-9795-e3678ba8e67b.gif' />

Assigning roles helps everyone know who’s doing what. An investigator is assigned first; the person responsible for figuring out what’s going on, or finding someone who can. For meatier incidents, a Commander is assigned, who takes charge of the incident, keeping everyone up-to-date and making sure nothing gets forgotten.

<img width='500' src='https://user-images.githubusercontent.com/101659/189378061-0750c211-cc38-42e3-8d23-037b903a9a28.gif' />

A chatbot offers a command-line interface for managing incidents. The chatbot also looks out for interesting context shared in the chat.

<img width="500" alt="Slackbot command help" src="https://user-images.githubusercontent.com/101659/189378082-0e2b445c-5d5c-46f4-b63a-9ea150fc66cb.png">

For example, if you post a link to a GitHub issue, it is attached to the incident and shows up on the page. Grafana Incident synchronises the status, so you can easily see what’s done and what’s left to do. Whether that’s GitHub issues and pull requests, JIRA tickets, Grafana dashboards, or external links, you can passively build up a picture of what’s going on.

<img width="500" alt="AttachContext" src="https://user-images.githubusercontent.com/101659/189378135-20357880-4929-4206-8cae-3a28766c5f7c.png">

Grafana Incident will even suggest related dashboards which is perfect for when it’s your first time on-call. Suggestbot uses machine learning to look for Grafana dashboards that may be related to what’s going on. Using the title of the incident, it searches your dashboards for those which seem related based on an NLP (Natural Language Processing) understanding of their titles. This is the first step in an exciting direction for Grafana Labs, and we can't wait to expand the insights into your incidents in the future.

<img width="500" alt="Suggestbot" src="https://user-images.githubusercontent.com/101659/189378304-4e50efe4-feb3-46a7-b3c4-7479c8c00794.png">

Keep track of TODO items with the built-in task manager. Easily add tasks and assign work, so nothing falls through the cracks.

<img width="500" alt="Task management is easy in Grafana Incident" src="https://user-images.githubusercontent.com/101659/189378347-9c24cc31-600e-4030-89d2-7a4339ff1105.gif">

he tool automatically builds a timeline of activity, helping you gain valuable insights into what went on, and how your response process is working, or not.

<img width='500' src='https://user-images.githubusercontent.com/101659/189378391-18238626-72f2-4fe5-98cf-8f25dbf2b2c5.png' />

Use the Present tool to discuss recent incidents for improved transparency, and giving you the opportunity to learn when things go wrong, and prevent them from happening again.

<img width='500' src='https://user-images.githubusercontent.com/101659/189378492-be9e833e-e11d-4830-92db-ff7142fd4dd8.gif' />
