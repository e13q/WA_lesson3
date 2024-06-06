# Short links and clics count

Utility for shortening links and for information (clics count, expanded link) about shortened links using VK API.
### How to install
 
Python3 should already be installed. 
Use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```
If you load project locally, then create `.env` file in project directory.

In .env write and fill `VK_SERVICE_ACCESS_KEY`.

If you load project on service (like replit) then just add a secret key `VK_SERVICE_ACCESS_KEY` and fill it.

Api key can be obtained via [instruction](https://id.vk.com/about/business/go/docs/ru/vkid/latest/vk-id/tokens/service-token).

Example:
`VK_SERVICE_ACCESS_KEY = '65cc8c6765cc8c6765cc8c67e466d4ebb4665fe65cc8c6703qwea96d78517798bcde495'`
### How to use

#### Windows OS

Open cmd/powershell/etc.

Change current directory in console to project directory by cd command.

Run script by command:

`py main.py url`

#### Linux OS

Open console.

Change current directory in console to project directory by cd command.

Run script by command:

`python3 main.py url`

### Examples of running script

Get shorten link

![Example4](https://github.com/e13q/WA_lesson3/assets/110967581/c77d104d-9eb8-43f4-b3e4-13844267dd09)

Get info about shorten link

![Example5](https://github.com/e13q/WA_lesson3/assets/110967581/c653a2a1-24f9-43be-a50e-87322ad39016)

### Project Goals

This code was written for educational purposes as part of an online course for web developers at [dvmn.org](https://dvmn.org/).
