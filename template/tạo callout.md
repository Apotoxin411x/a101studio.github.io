<%*
let selectedText = tp.file.selection();
if (selectedText) {
    let formattedText = ">[!note|aside-l]+\n" + selectedText.split("\n").map(line => "> " + line).join("\n");
    tR += formattedText;
} else {
    tR += "No text selected.";
}
-%>