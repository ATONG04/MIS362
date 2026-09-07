MIS362 GenAI02 / Student Hermes Starter Kit v2.0.7
Instructor review notes — September 7, 2026

DELIVERABLES
Student_Hermes_Starter_Kit_v2_0_7.zip contains all scripts, both PSD1 files,
README, three updated Word guides, context/reference/skill files, changelogs,
validation notes and SHA256 manifest.
GenAI02.html retains its filename and the instructor's latest edits.
GenAI02_Hermes_Setup_Verification_Template.md remains an optional checklist.

STUDENT PROCEDURE
Downloads -> Extract All -> copy the folder containing Docs/Scripts/README to
C:\Users\<StarID>\scripts -> rename MIS362_Student_Hermes_Starter_Kit ->
edit Scripts\StudentCourse_Config.psd1 -> open normal PowerShell 7:
  Set-Location "$HOME\scripts\MIS362_Student_Hermes_Starter_Kit\Scripts"
  .\000_Student_Setup.cmd
No automatic kit copying, running from Downloads, or required double-click.
After setup choose 2, capture one PASS screenshot, then 1, /quit, and 7.

REPORTED WSL ERROR
v2.0.5 expected an English WSL version label without explicitly decoding WSL's
native UTF-16 output. That can reject a working installation. v2.0.6 changed
the pattern but still used implicit pipe decoding. v2.0.7 reads bytes explicitly.
The exact cause on the laptop remains unconfirmed until its direct output and
the new run are reviewed. WSL minimum 2.1.5 and Docker isolation are retained.

EXISTING INSTALLATIONS: INSTRUCTOR-LED
Close Hermes/menu. Preserve the old installed kit under an unused backup name,
such as MIS362_Student_Hermes_Starter_Kit_previous_2_0_6.
Copy/rename the new kit to the standard location. Transfer only the five student
identifier VALUES into the new StudentCourse_Config.psd1. Do not replace the
new Course_Config.psd1 with an old one. Profiles/workspaces are separate.
Existing mis362hermes data is reused. An old mis362_student/MIS362_Student
profile or workspace stops for a guided naming transition; this release does
not migrate, merge or delete it. Resolve that plan before switching a student
who has an old working profile. Do not use reset 090 to troubleshoot setup.

HTML INTEGRATION
Exact form tag, attributes, IDs/names, hidden values, datasetContext, script
URLs, assignment ID/version and submission endpoints are preserved.
Instructor hardware/WSL image links, network-username link and revised Docker
UI wording are retained. Visible release/path/procedure text uses v2.0.7.
The hidden datasetContext still mentions v2.0.5; assignmentVersion remains
GenAI02-FA2026-v9. These machine-consumed values were preserved under the
established no-structural-change rule. Neither specifies the install path
nor changes the reflection task. Publish the optional checklist beside the HTML.

BEFORE CLASS
Pilot on the university Windows 11 image using exactly the student procedure.
Verify setup returns to the menu after any Hermes installation.
Choose option 2: profile mis362hermes, kit 2.0.7, installed Hermes version,
Docker Linux running, OpenRouter/openrouter/free, zero fallbacks, and PASS.
Choose 1, confirm terminal opens, /quit, then 7. Reopen the shortcut or installed
command to verify reuse without asking for the same key.
Check the published assignment and its submission integration.
Setup PASS does not prove an OpenRouter model/tool request succeeded; no
model-response test is required by this assignment.

OPEN QUESTIONS
1. What is the direct wsl --version output on the failing university laptop?
2. Which students already have old mis362_student/MIS362_Student profiles?
   Their work is preserved; a migration procedure is still needed for them.
3. Confirm that ClassStorage ID 20273000022 is correct for this section.
