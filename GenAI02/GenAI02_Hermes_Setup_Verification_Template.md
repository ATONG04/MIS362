# MIS362 GenAI02 Hermes Setup Verification

Optional checklist; no separate submission is required. Complete this file after Student Hermes Starter Kit v2.0.7 finishes setup. Record only non-secret configuration and verification results. Never paste an API key, password, token, `.env` contents, authentication screen, or private information into this file.

## Student-entered course configuration

- **Only `StudentCourse_Config.psd1` was edited:** Yes / No

- **CourseCode:** `MIS362`
- **StarID matches the Windows home-folder name:** Yes / No
- **NetworkUsername entered:** Yes / No
- **NetworkCourseID:** `20273000022`
- **GitHubUsername was left blank because GitEnabled is False:** Yes / No
- **OneDrive source existed and was synchronized before setup:** Yes / No

## Instructor-managed configuration observed

- **`Course_Config.psd1` remained unchanged:** Yes / No
- **GitEnabled:** `False`
- **Derived course source:** `OneDrive - Minnesota State\mis362hermes`
- **Starting provider/model:** `openrouter` / `openrouter/free`

## Starter-kit installation

- **Starter-kit version:** `2.0.7`
- **Installed kit folder:** `MIS362_Student_Hermes_Starter_Kit`
- **Setup was run as the normal Windows user, not Administrator:** Yes / No
- **`000_Student_Setup.cmd` completed without a blocking error:** Yes / No
- **`MIS362 Student Hermes` shortcut or installed command reopens the menu:** Yes / No

## Daily Menu option 2 status verification

- **ProfileName:** `mis362hermes`
- **Workspace is under `Hermes_Workspaces\mis362hermes`:** Yes / No
- **Installed Hermes version shown:**
- **Hermes version meets the starter-kit minimum:** Yes / No
- **Provider:** `openrouter`
- **Model:** `openrouter/free`
- **Fallback chain is empty:** Yes / No
- **Security settings:** PASS / FAIL
- **Docker sandbox:** PASS / NOT READY
- **Setup checks:** PASS / NOT READY
- **Docker:** Linux engine running / Not ready
- **Authoritative OneDrive source ends in `mis362hermes`:** Yes / No
- **API key or another secret is visible in the status evidence:** No

## Terminal Hermes launch verification

- **Daily Menu option 1 opened terminal Hermes:** Yes / No
- **Hermes opened in the `mis362hermes` environment:** Yes / No
- **Exited Hermes with `/quit`:** Yes / No
- **Exited the Daily Menu with option 7:** Yes / No

## Problems and corrections

Describe any problem reported during setup or status verification and what corrected it. If there was no problem, enter `None`.


## Docker isolation explanation

In three or four sentences, explain why Docker isolation is important, identify one location the container can access, identify one location or credential it cannot access, and describe one risk that still requires student judgment, approval, or verification.


## Readiness decision

- **Ready for GenAI03 through GenAI09:** Yes / No
- **Reason:**

## v2.0.7 manual installation check

- [ ] Extracted the ZIP in Downloads.
- [ ] Copied the inner kit folder to my Windows home scripts folder.
- [ ] Renamed it MIS362_Student_Hermes_Starter_Kit.
- [ ] Edited only the installed Scripts/StudentCourse_Config.psd1.
- [ ] Opened normal PowerShell 7 in installed Scripts; ran .\000_Student_Setup.cmd.
- [ ] Used option 2, then option 1, /quit, and option 7.
- [ ] Kept all API keys out of this checklist and course files.
