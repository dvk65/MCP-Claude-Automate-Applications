# MCP-Claude-Automate-Applications
<br>Trying to make job applications a combination of quality and quantity.<br>
<br>The final code would match keywords from resume, my interests and the job description and apply to those jobs.<br>

## Pre-requisites
1. Claude Desktop
2. Default bowser set to Google Chrome or Firefox

## Current steps to access browser
1. Open Claude Desktop settings and select developer options
2. Click on edit config and paste the config file from the repo. Replace username with your username
3. Test by accessing files on Desktop and giving Claude a command to open your browser
4. If this doesn't work immediately run this in your terminal
   ```npx @agent-infra/mcp-server-browser --port 8089```
5. The prompt I am using currently: "Search Google for New Grad Computer Science Roles. click on the jobs tab and click on the first posting. cancel or appropriately handle any other pop-ups. use the Dipti Kulkarni Resume.pdf file and Dipti Kulkarni Cover Letter.pdf to apply to the job. update the cover letter file by changing company name and their mission according to the job description."

## Things to do
1. File uploads not working
2. Look into integrating scripts to automate applying to more than one job
3. Maybe search jobs based on resume information to apply to more compatible jobs

## Resources:
<br>https://www.reddit.com/r/webdev/comments/1kb0dx1/how_to_use_claude_desktop_and_browser_mcp_to/<br>
<br>https://github.com/modelcontextprotocol<br>
<br><br>
