# GitHub CRM

How I use Github as my CRM to run my software business.

- Github - used as the central CRM, contains all tasks & tickets plus code
  - Uses Github Actions for some integrations and automation
- Google (Gmail, Calendar, Drive) as the office suite
  - Firebase - for static site hosting, CDN/Storage & Authentication
  - Google App Server - for node app hosting
  - Google Sheets for some simple integrations and storage of simple data like static sites form submissions
  - Google Analytics - analytics...
- WaveApps as the account, timetracking and invoicing software

Notice: This is a living document, starting out with my basic steps and will break it down more and supply tools as I go along.

## Geting started

First I created an [`organization`](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations) for my company in Github. This is the organization I will use for my team and any of my client's repo's will live here.

Install the following Github plugins and actions
- [weekly-digest](https://github.com/apps/weekly-digest)

## Clients & Projects

For each client a monorepo is created which contains all the different Projects associated with it. Also for ease to the client an e-mail is created that auto creates tickets for each client.


- [ ] Clone the following repo (coming soon)
- [ ] [Create e-mail for client using Fire](https://fire.fundersclub.com)
- [ ] Create WazeApp Customer
  - Add `Github` under 'Website' for ref
- [ ] Create associated Google Contact
  - Add 'Github' and the project URL for links to main contact
