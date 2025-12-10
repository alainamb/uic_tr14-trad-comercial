---
layout: default
title: LILT Translate Toolbar
parent: Semana 6
grand_parent: Unidad 2
nav_order: 4
---

# LILT Translate Toolbar

LILT Translate is a computer-aided translation (CAT) editor used to localize documents. LILT Translate incorporates a wealth of features and tools that enforce an efficient workflow for content translators and reviewers. The toolbar at the top has a range of options available for managing and customizing your experience with LILT Translate. Each tab of the header is described in the subsections below.

## File tab

![Lilt File Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_FileTab.png)

The `File` tab provides several actions to help manage documents.

* **Download:** Use this option to download the translated document in one of three formats:
  * **Option 1:** original format
  * **Option 2:** TXT format
  * **Option 3:** XLIFF format

* **Unlock document translation:** If the document has been locked for translation, the project manager can use this option to unlock the document in Translate mode so it can be worked on again by translators.

* **QA checks:** There are two types of QA checks that can be run from the `File` menu: full QA checks and linguistic batch QA checks.

## Edit tab

The `Edit` tab contains a list of commonly used actions to help speed up your work within LILT Translate.

![Lilt Edit Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_EditTab.png)

* **Undo (shortcut `Ctrl` + `Z`):** Undo the last edits that were made in the segment editor.

* **Select next word (`Shift` + `Tab`):** Select the next suggested word from the suggestion area below the typing text.

* **Concordance (`Ctrl` + `Alt` + `C`):** Opens the Concordance sidebar.

* **Find and Replace (`Ctrl` + `H`):** Search for text in all typing areas of the document. Includes the option to require the whole word to match, require the case to match, and to search through the entire Project instead of just the document.

![Lilt Find and Replace](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_FindAndReplace.png)

* **Highlight to change case (`Shift` + `F3`):** Changes the case of the currently selected section of target text.

## View tab

The `View` tab options affect how segments are displayed in LILT Translate.

![Lilt View Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_ViewTab.png)

* **Segments:**
  * Filter segments by status:
    * **All segments:** Segments with any confirmed/accepted status.
    * **Confirmed:** Segments that have been confirmed in Translate mode.
    * **Unconfirmed:** Segments that have **not** been confirmed in Translate mode.
    * **Unreviewed:** Segments that have **not** been accepted in Review mode.
    * **Reviewed:** Segments that have been accepted in Review mode.
    * **Changed:** Segments that have been modified and confirmed during the current user session.

  * Filter segments by additional content:
    * **Segments with notes:** Segments with notes added in Translate mode.
    * **Segments with errors:** Segments with errors added in Review mode.
    * **Segments with tags:** Segments that have tags in their content.
    * **Locked:** Segments that are confirmed, reviewed, or locked.

  * Both these filter sections compound with each other.
  * To remove a filter, click the filter again.

* **Previous segment (`Ctrl` + `Up Arrow`):** Navigate up through the document, segment by segment.

* **Next segment (`Ctrl` + `Down Arrow`):** Navigate down through the document, segment by segment.

* **Preview mode:** Toggles between segment edit mode and preview mode. Preview mode displays confirmed or accepted target segments with paragraph and HTML formatting.

* **Split view:** With split view disabled (the default setting), target text is displayed beneath the source text. If split view is enabled, target text is displayed to the right of the source text. Split view helps increase proofreading speed.

![Lilt Split View](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_SplitView.png)

* **Show invisible characters:** When enabled, displays characters that are normally invisible (such as spaces, tabs, right-to-left marks, and left-to-right marks) in both the source and target text.

![Lilt Show Invisible Characters](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_InvisibleCharacters.png)

## Insert tab

The `Insert` tab has a range of tools for interacting with text in the segment editor.

![Lilt Insert Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_InsertTab.png)

* **Suggested phrase (`Enter`):** Insert the suggested word into the target text field.

* **Full suggestion (`Shift` + `Enter`):** Insert the full suggested sentence into the target text field.

* **Non-breaking spaces (`Ctrl` + `Shift` + `Space`):** Insert a non-breaking space into the target text field. These can be useful in certain situations, as the non-breaking spaces do not get erased in document formats that ignore extra spaces, such as HTML.

* **Line break (`Alt` + `Enter`):** Adds a line break on the currently selected line in the target text field. Line breaks can also be copied from source text to target text by using the `Copy source to target` option in the segment editing tools.

* **Copy source to target (`Ctrl` + `I`):** Inserts the source text into the target text field. This is useful if a segment does not have to be translated for whatever reason.

* **Add new term (`Alt` + `A`):** Opens a popup where you can add a new translation entry to the associated Data Source.

* **Add comment (`Ctrl` + `Alt` + `M`):** Add a comment to the currently selected segment. These are the same comments you can add using the `View Note` button [image] next to a segment.

* **Insert right-to-left mark (`Ctrl` + `K`):** Inserts an invisible right-to-left mark character into the target text field. These are used to determine how the adjacent characters are grouped in respect to text direction.

* **Insert left-to-right mark (`Ctrl` + `L`):** Inserts an invisible left-to-right mark character into the target text field. These are used to determine how the adjacent characters are grouped in respect to text direction.

## Tags tab

The `Tag` tab provides tools for manipulating tags within the segment editor.

![Lilt Tags Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_TagsTab.png)

* **Show source tags:** Toggles whether tags in the source text are displayed.

* **Project target tags (`Ctrl` + `Alt` + `N`):** Projects target tags onto the segment.

* **Select next tag (`Ctrl` + `]`):** Navigate forward through tags.

* **Select previous tag (`Ctrl` + `[`):** Navigate backward through tags.

* **Select matching tags (`Alt` + `Shift`):** Toggle between which tag is selected in a matching pair of tags.

* **Move tag one word left (`M`):** Move the selected tag one word to the left area.

* **Move tag one word right (`/`):** Move the selected tag one word to the right.

* **Move tag one character left (`,`):** Move the selected tag one character to the left.

* **Move tag one character right (`.`):** Move the selected tag one character to the right.

## Settings tab

The `Settings` tab contains a variety of ways for you to customize the behavior of LILT Translate to suit your needs. These settings are set on a per-account basis, with changes persisting across documents and Projects.

![Lilt Settings Tab](https://raw.githubusercontent.com/alainamb/uic_tr14-trad-comercial/main/unidad2/semana7/imagenes/Lilt_SettingsTab.png)

* **Forward Overwrite Confirmed Segments and Backward Overwrite Confirmed Segments:** When enabled and a segment is confirmed, LILT uses the segment's target text to fill and replace the target text of other segments with matching source content forward/backward in the document. Overwrite Confirmed Segments always occurs for unconfirmed segments.

* **Keep sidebar open:** This option toggles whether the sidebar is kept open or not. By default, this is enabled.

* **Auto-scroll editor:** With auto-scroll on, when a segment is confirmed, LILT Translate automatically places you into editing the next segment and scrolls the page to keep the selected segment in view.

---

*Source: Adapted from [LILT Support Documentation](https://support.lilt.com/kb/introduction-to-lilt-translate)*
