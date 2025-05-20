# Website for Job-seeker
_*(Dự án vì cộng đồng - Cho đi là còn mãi)*_

#### ERM: https://drive.google.com/file/d/1vALJpP2X_oSY_WVrPI5oUdoctAiYA16V/view?usp=sharing
#### Database: https://docs.google.com/spreadsheets/d/1528j6HGfNB9T0CDV6Qq8I7WNC_tAe3iLBKPfgDShDn4/edit?usp=sharing#G1vALJpP2X_oSY_WVrPI5oUdoctAiYA16V#%7B%22pageId%22%3A%221IeiEe8-hJY0db8ghvol%22%7D
## OBJECTS
### Admin:
* General information management: Banner, sale, ...
* Users management
* Storing and managing files: JD, CV

### Recruiter:
* Post recruiting news
(Company, address, remote?, partime?, salary, language, other demand, file JD)
* Searching for CV
* Update personal information (related company, contacting information)

### Candidate:
* Searching for job, related company
(salary, address, language, certificate, level,number)
* Post CV
* Managing job list (in random order)
* Violation reports: company, personale
(cheat, spam, uncontactable, incorrect information)

## Functions analysis
### Post recruiting news

| Factor  | Recruiter |
| ------------- |:-------------:|
| Descript.     | post recruitment article     |
| Activate     | User hit/click button named “Post recruitment” on menu board   |
| Input      | Company name<br> Job name<br> Address: Cty - District (select2 - loading from local)<br> Is remote (radio)<br> Is partime (radio)<br> Salary (slide bar)<br> Language (multiple select2)<br> Further information (text)  |
| Process flow     | |
| Output      | Oui:<br>Redirect to management interface and alert successfull process<br>Non:<br>Redirect to login interface and alert error   |
| Note:     | *Regex: Validation rules for all input     |

## Copyright
_*dv89260*_

_*It's a free anw!*_
