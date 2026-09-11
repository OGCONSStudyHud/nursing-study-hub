<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">

<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0">

<title>OGCONS Study Hub - Admin Notes</title>

<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

<style>

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f1f3f6;
    color: #222;
}

/* =========================
   HEADER
========================= */

.header {
    background: #0b5ed7;
    color: white;
    padding: 18px 25px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 15px;
    flex-wrap: wrap;
}

.header h1 {
    margin: 0;
    font-size: 24px;
}

.back-admin-button {
    display: inline-block;
    padding: 14px 25px;
    font-size: 18px;
    font-weight: bold;
    border: none;
    border-radius: 10px;
    background: white;
    color: #0b5ed7;
    cursor: pointer;
}

.back-admin-button:hover {
    background: #e8f0ff;
}

/* =========================
   MAIN
========================= */

.container {
    width: 95%;
    max-width: 1200px;
    margin: 25px auto;
}

.panel {
    background: white;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 20px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

.panel h2 {
    margin-top: 0;
    color: #0b5ed7;
}

/* =========================
   FORM
========================= */

.form-row {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.form-group {
    flex: 1;
    min-width: 220px;
}

.form-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 7px;
}

select,
input[type="text"] {
    width: 100%;
    padding: 12px;
    border: 1px solid #bbb;
    border-radius: 7px;
    font-size: 15px;
}

button {
    font-family: inherit;
}

.main-button {
    padding: 12px 20px;
    border: none;
    border-radius: 7px;
    background: #0b5ed7;
    color: white;
    font-weight: bold;
    cursor: pointer;
}

.main-button:hover {
    background: #084298;
}

.danger-button {
    background: #dc3545;
}

.danger-button:hover {
    background: #bb2d3b;
}

.success-button {
    background: #198754;
}

.success-button:hover {
    background: #146c43;
}

/* =========================
   TOOLBAR
========================= */

.toolbar {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    padding: 10px;
    background: #f0f2f5;
    border: 1px solid #ccc;
    border-bottom: none;
    border-radius: 8px 8px 0 0;
}

.toolbar button,
.toolbar select {
    padding: 8px 10px;
    border: 1px solid #bbb;
    background: white;
    border-radius: 5px;
    cursor: pointer;
    font-size: 14px;
}

.toolbar button:hover {
    background: #e9ecef;
}

.toolbar-separator {
    width: 1px;
    background: #bbb;
    margin: 0 4px;
}

/* =========================
   EDITOR STAGE
   IMPORTANT:
   FIXED STARTING HEIGHT.
   DOES NOT GROW WITH TYPING.
========================= */

.editor-wrapper {
    width: 100%;
    overflow: auto;
    padding: 10px 0;
}

/*
    THIS IS THE WHITE PAPER.

    It starts at 700px.
    It does NOT automatically grow.

    The admin can manually expand it vertically
    using the resize handle at the bottom-right.
*/

.editor-stage {
    position: relative;

    width: 100%;
    max-width: 1000px;

    height: 700px;
    min-height: 500px;

    margin: 0 auto;

    background: #ffffff;

    border: 1px solid #cfcfcf;
    border-radius: 4px;

    overflow: auto;

    resize: vertical;

    box-sizing: border-box;
}

/*
    NORMAL WRITING AREA.

    It fills the current editor size.
    It DOES NOT increase the editor height.
*/

.writing-area {
    position: absolute;

    left: 0;
    top: 0;

    width: 100%;
    height: 100%;

    min-height: 100%;

    padding: 35px;

    background: #ffffff;

    outline: none;

    overflow: visible;

    z-index: 1;

    box-sizing: border-box;
}

/* =========================
   OBJECT LAYER
========================= */

.objects-layer {
    position: absolute;

    left: 0;
    top: 0;
    right: 0;
    bottom: 0;

    width: 100%;
    height: 100%;

    z-index: 5;

    pointer-events: none;
}

.design-object {
    position: absolute;

    pointer-events: auto;

    user-select: none;

    box-sizing: border-box;
}

.design-object.selected {
    outline: 2px solid #0b5ed7;
}

/* =========================
   TEXT BOX
========================= */

.text-object {
    min-width: 120px;
    min-height: 40px;

    padding: 8px;

    background: transparent;

    cursor: move;
}

.text-object.editing {
    cursor: text;
}

.text-content {
    width: 100%;
    min-height: 25px;

    outline: none;

    white-space: pre-wrap;

    word-wrap: break-word;
}

.text-object.editing .text-content {
    cursor: text;
}

/* =========================
   IMAGE
========================= */

.image-object {
    cursor: move;
}

.image-object img {
    display: block;

    width: 100%;
    height: 100%;

    object-fit: contain;

    pointer-events: none;

    user-select: none;
}

/* =========================
   TABLE
========================= */

.table-object {
    cursor: move;

    background: white;

    overflow: visible;
}

.table-object table {
    width: 100%;
    height: 100%;

    border-collapse: collapse;

    background: white;
}

.table-object td,
.table-object th {
    border: 1px solid #333;

    padding: 8px;

    min-width: 50px;

    outline: none;
}

.table-object td:focus,
.table-object th:focus {
    background: #eef5ff;
}

/* =========================
   SHAPES
========================= */

.shape-object {
    cursor: move;
}

.rectangle-shape {
    width: 100%;
    height: 100%;

    border: 3px solid #0b5ed7;

    background: rgba(11,94,215,0.05);
}

.circle-shape {
    width: 100%;
    height: 100%;

    border: 3px solid #198754;

    border-radius: 50%;

    background: rgba(25,135,84,0.05);
}

.line-shape {
    width: 100%;
    height: 4px;

    background: #222;
}

.arrow-shape {
    width: 100%;
    height: 4px;

    background: #dc3545;

    position: relative;
}

.arrow-shape::after {
    content: "";

    position: absolute;

    right: -2px;
    top: -7px;

    width: 0;
    height: 0;

    border-top: 9px solid transparent;
    border-bottom: 9px solid transparent;
    border-left: 16px solid #dc3545;
}

/* =========================
   OBJECT CONTROLS
========================= */

.object-controls {
    position: absolute;

    top: -35px;
    left: 0;

    display: flex;

    gap: 4px;

    background: #0b5ed7;

    padding: 4px;

    border-radius: 5px;

    z-index: 1000;
}

.object-controls button {
    border: none;

    background: white;

    color: #222;

    width: 27px;
    height: 27px;

    border-radius: 4px;

    cursor: pointer;

    font-size: 14px;
}

.object-controls button:hover {
    background: #e9ecef;
}

/* =========================
   RESIZE HANDLE
========================= */

.resize-handle {
    position: absolute;

    right: -7px;
    bottom: -7px;

    width: 14px;
    height: 14px;

    background: #0b5ed7;

    border: 2px solid white;

    border-radius: 50%;

    cursor: nwse-resize;

    z-index: 1001;
}

/* =========================
   ROTATE HANDLE
========================= */

.rotate-handle {
    position: absolute;

    left: 50%;
    top: -35px;

    transform: translateX(-50%);

    width: 18px;
    height: 18px;

    background: #198754;

    border: 2px solid white;

    border-radius: 50%;

    cursor: grab;

    z-index: 1001;
}

.rotate-handle::after {
    content: "↻";

    position: absolute;

    color: white;

    font-size: 12px;

    left: 1px;
    top: -1px;
}

/* =========================
   SEARCH
========================= */

.search-row {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.search-row input {
    flex: 1;
    min-width: 250px;
}

.note-count {
    margin-top: 10px;
    color: #666;
    font-size: 14px;
}

/* =========================
   NOTES LIST
========================= */

.notes-grid {
    display: grid;

    grid-template-columns:
        repeat(auto-fill, minmax(280px, 1fr));

    gap: 15px;

    margin-top: 15px;
}

.note-card {
    border: 1px solid #ddd;

    border-radius: 10px;

    padding: 15px;

    background: white;
}

.note-card h3 {
    margin-top: 0;

    color: #0b5ed7;
}

.note-card p {
    color: #666;
}

.note-preview {
    max-height: 150px;

    overflow: hidden;

    margin-bottom: 12px;

    font-size: 14px;
}

.note-card-buttons {
    display: flex;

    gap: 8px;

    flex-wrap: wrap;
}

/* =========================
   STATUS
========================= */

.status {
    margin-top: 15px;

    padding: 10px;

    border-radius: 6px;

    display: none;
}

.status.success {
    display: block;

    background: #d1e7dd;

    color: #0f5132;
}

.status.error {
    display: block;

    background: #f8d7da;

    color: #842029;
}

/* =========================
   PREVIEW
========================= */

.preview-box {
    display: none;

    position: fixed;

    inset: 0;

    background: rgba(0,0,0,0.7);

    z-index: 5000;

    overflow: auto;

    padding: 30px;
}

.preview-inner {
    background: white;

    max-width: 1000px;

    margin: auto;

    padding: 30px;

    min-height: 500px;
}

.close-preview {
    position: fixed;

    top: 15px;
    right: 20px;

    background: #dc3545;

    color: white;

    border: none;

    padding: 12px 18px;

    border-radius: 6px;

    cursor: pointer;

    z-index: 5001;
}

/* =========================
   MOBILE
========================= */

@media(max-width:700px) {

    .header {
        padding: 15px;
    }

    .header h1 {
        font-size: 20px;
    }

    .back-admin-button {
        font-size: 16px;
        padding: 12px 18px;
    }

    .container {
        width: 98%;
    }

    .editor-stage {
        height: 700px;
    }

    .writing-area {
        padding: 20px;
    }

}

</style>

</head>

<body>

<!-- =========================
     HEADER
========================= -->

<header class="header">

    <h1>OGCONS Study Hub - Admin Notes</h1>

    <button
        class="back-admin-button"
        onclick="window.location.href='admin.html'">

        ← Back to Main Admin

    </button>

</header>


<div class="container">


<!-- =========================
     NOTE INFORMATION
========================= -->

<div class="panel">

    <h2>Note Information</h2>

    <div class="form-row">

        <div class="form-group">

            <label>Course</label>

            <select id="course">

                <option value="">Select Course</option>

                <option value="Foundations of Nursing">
                    Foundations of Nursing
                </option>

                <option value="Anatomy & Physiology">
                    Anatomy & Physiology
                </option>

                <option value="Pharmacology">
                    Pharmacology
                </option>

                <option value="Primary Health Care">
                    Primary Health Care
                </option>

                <option value="Medical/Surgical Nursing">
                    Medical/Surgical Nursing
                </option>

                <option value="Microbiology">
                    Microbiology
                </option>

            </select>

        </div>


        <div class="form-group">

            <label>Topic</label>

            <select id="topic">

                <option value="">Select Topic</option>

            </select>

        </div>


        <div class="form-group">

            <label>Note Title</label>

            <input
                type="text"
                id="title"
                placeholder="Enter note title">

        </div>

    </div>

</div>


<!-- =========================
     EDITOR
========================= -->

<div class="panel">

    <h2>Note Editor</h2>


    <div class="toolbar">

        <button onclick="formatText('bold')">
            <b>B</b>
        </button>

        <button onclick="formatText('italic')">
            <i>I</i>
        </button>

        <button onclick="formatText('underline')">
            <u>U</u>
        </button>


        <select onchange="formatBlock(this.value); this.selectedIndex=0;">

            <option value="">Heading</option>

            <option value="h1">Heading 1</option>

            <option value="h2">Heading 2</option>

            <option value="h3">Heading 3</option>

            <option value="p">Normal</option>

        </select>


        <select onchange="changeFontSize(this.value); this.selectedIndex=0;">

            <option value="">Text Size</option>

            <option value="1">Small</option>

            <option value="3">Normal</option>

            <option value="5">Large</option>

            <option value="6">Very Large</option>

            <option value="7">Huge</option>

        </select>


        <div class="toolbar-separator"></div>


        <button onclick="formatText('justifyLeft')">
            ⬅
        </button>

        <button onclick="formatText('justifyCenter')">
            ↔
        </button>

        <button onclick="formatText('justifyRight')">
            ➡
        </button>


        <button onclick="formatText('insertUnorderedList')">
            • List
        </button>

        <button onclick="formatText('insertOrderedList')">
            1. List
        </button>


        <div class="toolbar-separator"></div>


        <button onclick="addTextBox()">
            Text Box
        </button>

        <button onclick="addImage()">
            Image
        </button>

        <button onclick="addTable()">
            Table
        </button>


        <div class="toolbar-separator"></div>


        <button onclick="addShape('rectangle')">
            Rectangle
        </button>

        <button onclick="addShape('circle')">
            Circle
        </button>

        <button onclick="addShape('line')">
            Line
        </button>

        <button onclick="addShape('arrow')">
            Arrow
        </button>


        <div class="toolbar-separator"></div>


        <button onclick="formatText('insertHorizontalRule')">
            ─ Line
        </button>

        <button onclick="addLink()">
            Link
        </button>

        <button onclick="formatText('formatBlock','blockquote')">
            Quote
        </button>


        <div class="toolbar-separator"></div>


        <button onclick="formatText('undo')">
            ↶ Undo
        </button>

        <button onclick="formatText('redo')">
            ↷ Redo
        </button>


        <button onclick="previewNote()">
            Preview
        </button>

    </div>


    <!--
        IMPORTANT:

        This editor starts at 700px.

        It WILL NOT grow when typing.

        The admin manually expands it using
        the resize handle at the bottom-right.
    -->

    <div class="editor-wrapper">

        <div
            id="editorStage"
            class="editor-stage">

            <div
                id="writingArea"
                class="writing-area"
                contenteditable="true">

            </div>


            <div
                id="objectsLayer"
                class="objects-layer">

            </div>

        </div>

    </div>


    <br>


    <div>

        <button
            class="main-button success-button"
            onclick="saveNote()">

            Save Note

        </button>


        <button
            class="main-button"
            onclick="clearEditor()">

            Clear

        </button>

    </div>


    <div
        id="status"
        class="status">

    </div>

</div>


<!-- =========================
     SEARCH NOTES
========================= -->

<div class="panel">

    <h2>Search Notes</h2>

    <div class="search-row">

        <input
            type="text"
            id="searchInput"
            placeholder="Search by title, course or topic..."
            oninput="loadNotes()">


        <button
            class="main-button"
            onclick="clearSearch()">

            Clear Search

        </button>

    </div>


    <div
        id="noteCount"
        class="note-count">

        Loading notes...

    </div>


    <div
        id="notesList"
        class="notes-grid">

    </div>

</div>

</div>


<!-- =========================
     PREVIEW
========================= -->

<div
    id="previewBox"
    class="preview-box">

    <button
        class="close-preview"
        onclick="closePreview()">

        Close

    </button>


    <div
        id="previewInner"
        class="preview-inner">

    </div>

</div>


<script>

/* =====================================================
   SUPABASE
===================================================== */

const SUPABASE_URL =
"https://bvetmmvpdotifusjkywd.supabase.co";

const SUPABASE_KEY =
"sb_publishable_1bssTw_8JM3HtHD3KoaL5w_iCwaLMYS";

const supabaseClient =
    window.supabase.createClient(
        SUPABASE_URL,
        SUPABASE_KEY
    );


/* =====================================================
   COURSE TOPICS
===================================================== */

const courseTopics = {

    "Foundations of Nursing": [

        "Introduction to Nursing",

        "Health Care Institutions",

        "Ethico-Legal Issues in Nursing",

        "Tools of Nursing",

        "Comfort and Safety Measures",

        "Emergency Care",

        "Administration of Drugs",

        "Diagnostic Investigation",

        "Aseptic Techniques",

        "Unsafe Injection Safety",

        "Introduction to Healthcare Waste",

        "Legal Aspects of Nursing",

        "Nursing Care of Patients with Feeding/Elimination Problems",

        "Basic Life Support"

    ],


    "Anatomy & Physiology": [

        "Introduction to Anatomy",

        "The Musculoskeletal System",

        "Blood and Cardiovascular System",

        "The Respiratory System",

        "The Digestive System",

        "The Integumentary System",

        "The Excretory System",

        "The Endocrine System",

        "The Female Reproductive System",

        "The Male Reproductive System",

        "Foetal Development"

    ],


    "Pharmacology": [

        "Introduction",

        "Sources and Classification of Drugs",

        "Preparation of Drugs",

        "Routes of Drug Administration",

        "Mechanism of Drug Action",

        "National Drug Policy",

        "Drugs Used in Management of Other Health Conditions",

        "Patient Education and Counseling"

    ],


    "Primary Health Care": [

        "Introduction to Primary Health Care",

        "The Community",

        "Cadre of Health Workers in PHC",

        "Community Mobilization",

        "Community Diagnosis",

        "Health Education",

        "Components of Primary Health Care",

        "Immunization Against Major Communicable Diseases",

        "Prevention and Control of Locally Endemic and Epidemic Diseases",

        "Promotion of Mental Health",

        "Maternal and Child Health Services",

        "Provision of Essential Drugs and Supplies",

        "Oral Hygiene and Eye Care",

        "Adolescence and Their Problems",

        "Referral System in PHC",

        "Care of the Aged in the Community",

        "Management of Occupational Health",

        "Management in Primary Health Care"

    ],


    "Medical/Surgical Nursing": [

        "Concepts and Terms in Medical-Surgical Nursing",

        "Management of Patients with Medical/Surgical Conditions",

        "Management of Patients with Medical/Surgical Conditions 2",

        "Common Situations That Threaten Adaptation",

        "Body Defense Mechanisms",

        "Diagnostic Measures",

        "Principles of Operating Room Nursing"

    ],


    "Microbiology": [

        "Introduction to Microbiology",

        "Bacteria",

        "Viruses",

        "Fungi",

        "Parasites",

        "Immunology",

        "Sterilization & Disinfection",

        "Healthcare-Associated Infections"

    ]

};


/* =====================================================
   CURRENT NOTE
===================================================== */

let currentNoteId = null;

let selectedObject = null;

let dragging = false;

let resizing = false;

let rotating = false;

let dragStartX = 0;

let dragStartY = 0;

let objectStartX = 0;

let objectStartY = 0;

let objectStartWidth = 0;

let objectStartHeight = 0;

let startAngle = 0;


/* =====================================================
   COURSE CHANGE
===================================================== */

document
    .getElementById("course")
    .addEventListener("change", function(){

        const course = this.value;

        const topicSelect =
            document.getElementById("topic");

        topicSelect.innerHTML =
            '<option value="">Select Topic</option>';


        if (!course) return;


        courseTopics[course].forEach(function(topic){

            const option =
                document.createElement("option");

            option.value = topic;

            option.textContent = topic;

            topicSelect.appendChild(option);

        });

    });


/* =====================================================
   BASIC TEXT FORMATTING
===================================================== */

function formatText(command, value = null){

    document
        .getElementById("writingArea")
        .focus();

    document.execCommand(
        command,
        false,
        value
    );
}


function formatBlock(value){

    if (!value) return;

    document
        .getElementById("writingArea")
        .focus();

    document.execCommand(
        "formatBlock",
        false,
        value
    );
}


function changeFontSize(value){

    if (!value) return;

    document
        .getElementById("writingArea")
        .focus();

    document.execCommand(
        "fontSize",
        false,
        value
    );
}


/* =====================================================
   LINK
===================================================== */

function addLink(){

    const url =
        prompt("Enter the link:");

    if (!url) return;

    formatText(
        "createLink",
        url
    );
}


/* =====================================================
   ADD TEXT BOX
===================================================== */

function addTextBox(){

    const stage =
        document.getElementById("editorStage");

    const layer =
        document.getElementById("objectsLayer");


    const box =
        document.createElement("div");

    box.className =
        "design-object text-object";

    box.style.left = "100px";

    box.style.top = "100px";

    box.style.width = "300px";

    box.style.minHeight = "50px";


    const content =
        document.createElement("div");

    content.className =
        "text-content";

    content.contentEditable = "true";

    content.innerHTML =
        "Type your text here";


    box.appendChild(content);

    layer.appendChild(box);


    makeObjectInteractive(box);

    selectObject(box);

    enterTextEdit(box);

}


/* =====================================================
   ADD IMAGE
===================================================== */

function addImage(){

    const input =
        document.createElement("input");

    input.type = "file";

    input.accept =
        "image/*";


    input.onchange =
        function(){

            const file =
                this.files[0];

            if (!file) return;


            const reader =
                new FileReader();


            reader.onload =
                function(e){

                    const layer =
                        document.getElementById(
                            "objectsLayer"
                        );


                    const box =
                        document.createElement("div");

                    box.className =
                        "design-object image-object";


                    box.style.left =
                        "100px";

                    box.style.top =
                        "100px";

                    box.style.width =
                        "350px";

                    box.style.height =
                        "250px";


                    const img =
                        document.createElement("img");

                    img.src =
                        e.target.result;


                    box.appendChild(img);

                    layer.appendChild(box);


                    makeObjectInteractive(box);

                    selectObject(box);

                };


            reader.readAsDataURL(file);

        };


    input.click();

}


/* =====================================================
   ADD TABLE
===================================================== */

function addTable(){

    const rows =
        parseInt(
            prompt("Number of rows:", "3")
        );


    const cols =
        parseInt(
            prompt("Number of columns:", "3")
        );


    if (
        !rows ||
        !cols ||
        rows < 1 ||
        cols < 1
    ) return;


    const layer =
        document.getElementById(
            "objectsLayer"
        );


    const box =
        document.createElement("div");

    box.className =
        "design-object table-object";


    box.style.left =
        "100px";

    box.style.top =
        "100px";

    box.style.width =
        "500px";

    box.style.height =
        "250px";


    const table =
        document.createElement("table");


    for(let r = 0; r < rows; r++){

        const tr =
            document.createElement("tr");


        for(let c = 0; c < cols; c++){

            const td =
                document.createElement("td");

            td.contentEditable =
                "true";

            td.innerHTML =
                "Cell";


            tr.appendChild(td);

        }


        table.appendChild(tr);

    }


    box.appendChild(table);

    layer.appendChild(box);


    makeObjectInteractive(box);

    selectObject(box);

}


/* =====================================================
   ADD SHAPE
===================================================== */

function addShape(type){

    const layer =
        document.getElementById(
            "objectsLayer"
        );


    const box =
        document.createElement("div");


    box.className =
        "design-object shape-object";


    box.style.left =
        "150px";

    box.style.top =
        "150px";

    box.style.width =
        type === "line" ||
        type === "arrow"
            ? "300px"
            : "200px";


    box.style.height =
        type === "line" ||
        type === "arrow"
            ? "20px"
            : "150px";


    const shape =
        document.createElement("div");


    if(type === "rectangle"){

        shape.className =
            "rectangle-shape";

    }

    if(type === "circle"){

        shape.className =
            "circle-shape";

    }

    if(type === "line"){

        shape.className =
            "line-shape";

    }

    if(type === "arrow"){

        shape.className =
            "arrow-shape";

    }


    box.appendChild(shape);

    layer.appendChild(box);


    makeObjectInteractive(box);

    selectObject(box);

}


/* =====================================================
   SELECT OBJECT
===================================================== */

function selectObject(object){

    if(selectedObject){

        selectedObject.classList
            .remove("selected");

        removeControls(
            selectedObject
        );

    }


    selectedObject =
        object;


    object.classList
        .add("selected");


    addControls(object);

}


/* =====================================================
   CONTROLS
===================================================== */

function addControls(object){

    removeControls(object);


    const controls =
        document.createElement("div");

    controls.className =
        "object-controls";


    const left =
        document.createElement("button");

    left.textContent =
        "←";

    left.onclick =
        function(e){

            e.stopPropagation();

            object.style.left =
                Math.max(
                    0,
                    object.offsetLeft - 10
                ) + "px";

        };


    const center =
        document.createElement("button");

    center.textContent =
        "↔";

    center.onclick =
        function(e){

            e.stopPropagation();

            const stage =
                document.getElementById(
                    "editorStage"
                );

            object.style.left =
                Math.max(
                    0,
                    (stage.clientWidth -
                        object.offsetWidth) / 2
                ) + "px";

        };


    const right =
        document.createElement("button");

    right.textContent =
        "→";

    right.onclick =
        function(e){

            e.stopPropagation();

            const stage =
                document.getElementById(
                    "editorStage"
                );

            object.style.left =
                Math.max(
                    0,
                    stage.clientWidth -
                    object.offsetWidth -
                    10
                ) + "px";

        };


    const deleteButton =
        document.createElement("button");

    deleteButton.textContent =
        "🗑";

    deleteButton.onclick =
        function(e){

            e.stopPropagation();

            object.remove();

            selectedObject =
                null;

        };


    controls.appendChild(left);

    controls.appendChild(center);

    controls.appendChild(right);

    controls.appendChild(deleteButton);


    object.appendChild(
        controls
    );


    const resize =
        document.createElement("div");

    resize.className =
        "resize-handle";


    object.appendChild(
        resize
    );


    const rotate =
        document.createElement("div");

    rotate.className =
        "rotate-handle";


    object.appendChild(
        rotate
    );


    resize.addEventListener(
        "mousedown",
        startResize
    );


    rotate.addEventListener(
        "mousedown",
        startRotate
    );

}


/* =====================================================
   REMOVE CONTROLS
===================================================== */

function removeControls(object){

    if(!object) return;

    object
        .querySelectorAll(
            ".object-controls,.resize-handle,.rotate-handle"
        )
        .forEach(function(el){

            el.remove();

        });

}


/* =====================================================
   TEXT EDITING
===================================================== */

function enterTextEdit(object){

    if(
        !object.classList.contains(
            "text-object"
        )
    ) return;


    object.classList
        .add("editing");


    const content =
        object.querySelector(
            ".text-content"
        );


    if(content){

        content.contentEditable =
            "true";

        content.focus();


        const range =
            document.createRange();

        range.selectNodeContents(
            content
        );

        range.collapse(false);


        const selection =
            window.getSelection();

        selection.removeAllRanges();

        selection.addRange(range);

    }

}


function exitTextEdit(object){

    if(!object) return;


    if(
        !object.classList.contains(
            "text-object"
        )
    ) return;


    object.classList
        .remove("editing");


    const content =
        object.querySelector(
            ".text-content"
        );


    if(content){

        content.contentEditable =
            "false";

    }

}


/* =====================================================
   OBJECT INTERACTION
===================================================== */

function makeObjectInteractive(object){

    object.addEventListener(
        "mousedown",
        function(e){

            if(
                e.target.closest(
                    ".object-controls"
                ) ||
                e.target.closest(
                    ".resize-handle"
                ) ||
                e.target.closest(
                    ".rotate-handle"
                )
            ){

                return;

            }


            if(
                object.classList.contains(
                    "text-object"
                ) &&
                object.classList.contains(
                    "editing"
                )
            ){

                return;

            }


            e.preventDefault();

            selectObject(object);


            dragging = true;


            dragStartX =
                e.clientX;

            dragStartY =
                e.clientY;


            objectStartX =
                object.offsetLeft;

            objectStartY =
                object.offsetTop;

        }
    );


    object.addEventListener(
        "dblclick",
        function(e){

            if(
                object.classList.contains(
                    "text-object"
                )
            ){

                e.stopPropagation();

                enterTextEdit(object);

            }

        }
    );

}


/* =====================================================
   GLOBAL MOUSE MOVE
===================================================== */

document.addEventListener(
    "mousemove",
    function(e){

        if(!selectedObject)
            return;


        if(dragging){

            const dx =
                e.clientX -
                dragStartX;

            const dy =
                e.clientY -
                dragStartY;


            selectedObject.style.left =
                Math.max(
                    0,
                    objectStartX + dx
                ) + "px";


            selectedObject.style.top =
                Math.max(
                    0,
                    objectStartY + dy
                ) + "px";

        }


        if(resizing){

            const dx =
                e.clientX -
                dragStartX;

            const dy =
                e.clientY -
                dragStartY;


            selectedObject.style.width =
                Math.max(
                    50,
                    objectStartWidth + dx
                ) + "px";


            selectedObject.style.height =
                Math.max(
                    30,
                    objectStartHeight + dy
                ) + "px";

        }


        if(rotating){

            const rect =
                selectedObject.getBoundingClientRect();


            const centerX =
                rect.left +
                rect.width / 2;


            const centerY =
                rect.top +
                rect.height / 2;


            const angle =
                Math.atan2(
                    e.clientY - centerY,
                    e.clientX - centerX
                ) *
                180 /
                Math.PI;


            const rotation =
                angle -
                startAngle;


            selectedObject.dataset.rotation =
                rotation;


            selectedObject.style.transform =
                "rotate(" +
                rotation +
                "deg)";

        }

    }
);


/* =====================================================
   GLOBAL MOUSE UP
===================================================== */

document.addEventListener(
    "mouseup",
    function(){

        dragging = false;

        resizing = false;

        rotating = false;

    }
);


/* =====================================================
   RESIZE
===================================================== */

function startResize(e){

    e.preventDefault();

    e.stopPropagation();


    if(!selectedObject)
        return;


    resizing = true;


    dragStartX =
        e.clientX;

    dragStartY =
        e.clientY;


    objectStartWidth =
        selectedObject.offsetWidth;

    objectStartHeight =
        selectedObject.offsetHeight;

}


/* =====================================================
   ROTATE
===================================================== */

function startRotate(e){

    e.preventDefault();

    e.stopPropagation();


    if(!selectedObject)
        return;


    rotating = true;


    const rect =
        selectedObject.getBoundingClientRect();


    const centerX =
        rect.left +
        rect.width / 2;


    const centerY =
        rect.top +
        rect.height / 2;


    startAngle =
        Math.atan2(
            e.clientY - centerY,
            e.clientX - centerX
        ) *
        180 /
        Math.PI;

}


/* =====================================================
   CLICK OUTSIDE
===================================================== */

document
    .getElementById("editorStage")
    .addEventListener(
        "mousedown",
        function(e){

            if(
                e.target ===
                document.getElementById(
                    "editorStage"
                )
            ){

                if(selectedObject){

                    exitTextEdit(
                        selectedObject
                    );

                }

            }

        }
    );


document.addEventListener(
    "mousedown",
    function(e){

        if(
            selectedObject &&
            !selectedObject.contains(e.target)
        ){

            if(
                selectedObject.classList
                    .contains("editing")
            ){

                exitTextEdit(
                    selectedObject
                );

            }

        }

    }
);


/* =====================================================
   SAVE NOTE
===================================================== */

async function saveNote(){

    const course =
        document.getElementById(
            "course"
        ).value;


    const topic =
        document.getElementById(
            "topic"
        ).value;


    const title =
        document.getElementById(
            "title"
        ).value.trim();


    if(!course){

        showStatus(
            "Please select a course.",
            "error"
        );

        return;

    }


    if(!topic){

        showStatus(
            "Please select a topic.",
            "error"
        );

        return;

    }


    if(!title){

        showStatus(
            "Please enter a note title.",
            "error"
        );

        return;

    }


    const content =
        prepareHTMLForSaving();


    if(!content){

        showStatus(
            "Please enter some note content.",
            "error"
        );

        return;

    }


    try{

        let result;


        if(currentNoteId){

            result =
                await supabaseClient
                    .from("notes")
                    .update({

                        course:
                            course,

                        topic:
                            topic,

                        title:
                            title,

                        content:
                            content,

                        updated_at:
                            new Date().toISOString()

                    })
                    .eq(
                        "id",
                        currentNoteId
                    );

        }else{

            result =
                await supabaseClient
                    .from("notes")
                    .insert({

                        course:
                            course,

                        topic:
                            topic,

                        title:
                            title,

                        content:
                            content

                    });

        }


        if(result.error)
            throw result.error;


        showStatus(
            "Note saved successfully.",
            "success"
        );


        currentNoteId =
            null;


        loadNotes();

    }catch(error){

        console.error(error);

        showStatus(
            error.message ||
            "Unable to save note.",
            "error"
        );

    }

}


/* =====================================================
   PREPARE HTML
===================================================== */

function prepareHTMLForSaving(){

    const stage =
        document.getElementById(
            "editorStage"
        );


    const writing =
        document.getElementById(
            "writingArea"
        );


    const objects =
        document.getElementById(
            "objectsLayer"
        );


    /*
        IMPORTANT:

        Use the CURRENT manually chosen height.

        DO NOT use scrollHeight.

        This means the admin controls
        the note page height.
    */

    const designHeight =
        stage.clientHeight;


    if(
        !writing.innerHTML.trim() &&
        objects.children.length === 0
    ){

        return "";

    }


    const canvas =
        document.createElement("div");


    canvas.className =
        "ogcons-note-canvas";


    canvas.style.position =
        "relative";


    canvas.style.width =
        "1000px";


    canvas.style.height =
        designHeight + "px";


    canvas.style.minHeight =
        designHeight + "px";


    canvas.style.background =
        "#ffffff";


    canvas.style.boxSizing =
        "border-box";


    canvas.style.overflow =
        "visible";


    /*
        WRITING LAYER
    */

    const savedWriting =
        document.createElement("div");


    savedWriting.className =
        "ogcons-writing-layer";


    savedWriting.innerHTML =
        writing.innerHTML;


    savedWriting.style.position =
        "absolute";


    savedWriting.style.left =
        "0";


    savedWriting.style.top =
        "0";


    savedWriting.style.width =
        "100%";


    savedWriting.style.height =
        "100%";


    savedWriting.style.padding =
        "35px";


    savedWriting.style.boxSizing =
        "border-box";


    savedWriting.style.background =
        "#ffffff";


    canvas.appendChild(
        savedWriting
    );


    /*
        OBJECTS LAYER
    */

    const savedObjects =
        document.createElement("div");


    savedObjects.className =
        "ogcons-objects-layer";


    savedObjects.style.position =
        "absolute";


    savedObjects.style.left =
        "0";


    savedObjects.style.top =
        "0";


    savedObjects.style.width =
        "100%";


    savedObjects.style.height =
        "100%";


    savedObjects.style.pointerEvents =
        "none";


    canvas.appendChild(
        savedObjects
    );


    /*
        COPY DESIGN OBJECTS
    */

    Array.from(
        objects.children
    ).forEach(function(object){

        const clone =
            object.cloneNode(true);


        clone
            .querySelectorAll(
                ".object-controls,.resize-handle,.rotate-handle"
            )
            .forEach(function(el){

                el.remove();

            });


        clone.style.pointerEvents =
            "auto";


        clone.style.position =
            "absolute";


        clone.style.left =
            object.offsetLeft + "px";


        clone.style.top =
            object.offsetTop + "px";


        clone.style.width =
            object.offsetWidth + "px";


        clone.style.height =
            object.offsetHeight + "px";


        if(
            object.dataset.rotation
        ){

            clone.style.transform =
                "rotate(" +
                object.dataset.rotation +
                "deg)";

        }


        savedObjects.appendChild(
            clone
        );

    });


    /*
        RESPONSIVE DISPLAY CSS
    */

    const style =
        document.createElement("style");


    style.textContent = `

        .ogcons-note-canvas {
            position: relative;
            width: 1000px;
            max-width: 100%;
            background: #ffffff;
            box-sizing: border-box;
            overflow: visible;
        }

        .ogcons-writing-layer {
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            box-sizing: border-box;
            background: #ffffff;
        }

        .ogcons-objects-layer {
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }

        .ogcons-objects-layer > * {
            pointer-events: auto;
        }

        .text-object {
            position: absolute;
            box-sizing: border-box;
            white-space: pre-wrap;
        }

        .image-object img {
            display: block;
            width: 100%;
            height: 100%;
            object-fit: contain;
        }

        .table-object table {
            width: 100%;
            height: 100%;
            border-collapse: collapse;
        }

        .table-object td,
        .table-object th {
            border: 1px solid #333;
            padding: 8px;
        }

        .rectangle-shape {
            width: 100%;
            height: 100%;
            border: 3px solid #0b5ed7;
            background: rgba(11,94,215,0.05);
        }

        .circle-shape {
            width: 100%;
            height: 100%;
            border: 3px solid #198754;
            border-radius: 50%;
            background: rgba(25,135,84,0.05);
        }

        .line-shape {
            width: 100%;
            height: 4px;
            background: #222;
        }

        .arrow-shape {
            width: 100%;
            height: 4px;
            background: #dc3545;
            position: relative;
        }

        .arrow-shape::after {
            content: "";
            position: absolute;
            right: -2px;
            top: -7px;
            width: 0;
            height: 0;
            border-top: 9px solid transparent;
            border-bottom: 9px solid transparent;
            border-left: 16px solid #dc3545;
        }

    `;


    canvas.appendChild(
        style
    );


    return canvas.outerHTML;

}


/* =====================================================
   LOAD NOTES
===================================================== */

async function loadNotes(){

    const list =
        document.getElementById(
            "notesList"
        );


    const count =
        document.getElementById(
            "noteCount"
        );


    const search =
        document.getElementById(
            "searchInput"
        )
        .value
        .trim()
        .toLowerCase();


    list.innerHTML =
        "Loading...";


    let query =
        supabaseClient
            .from("notes")
            .select("*")
            .order(
                "created_at",
                {
                    ascending: false
                }
            );


    const result =
        await query;


    if(result.error){

        list.innerHTML =
            "<p>Unable to load notes.</p>";

        return;

    }


    let notes =
        result.data || [];


    if(search){

        notes =
            notes.filter(function(note){

                return (

                    String(
                        note.title || ""
                    )
                    .toLowerCase()
                    .includes(search)

                    ||

                    String(
                        note.course || ""
                    )
                    .toLowerCase()
                    .includes(search)

                    ||

                    String(
                        note.topic || ""
                    )
                    .toLowerCase()
                    .includes(search)

                );

            });

    }


    count.textContent =
        notes.length +
        " note(s) found";


    if(!notes.length){

        list.innerHTML =
            "<p>No notes found.</p>";

        return;

    }


    list.innerHTML = "";


    notes.forEach(function(note){

        const card =
            document.createElement("div");


        card.className =
            "note-card";


        const heading =
            document.createElement("h3");


        heading.textContent =
            note.title;


        const course =
            document.createElement("p");


        course.innerHTML =
            "<strong>Course:</strong> " +
            escapeHTML(
                note.course
            );


        const topic =
            document.createElement("p");


        topic.innerHTML =
            "<strong>Topic:</strong> " +
            escapeHTML(
                note.topic
            );


        const preview =
            document.createElement("div");


        preview.className =
            "note-preview";


        preview.innerHTML =
            note.content || "";


        const buttons =
            document.createElement("div");


        buttons.className =
            "note-card-buttons";


        const edit =
            document.createElement("button");


        edit.className =
            "main-button";


        edit.textContent =
            "Edit";


        edit.onclick =
            function(){

                editNote(note);

            };


        const remove =
            document.createElement("button");


        remove.className =
            "main-button danger-button";


        remove.textContent =
            "Delete";


        remove.onclick =
            function(){

                deleteNote(note.id);

            };


        buttons.appendChild(
            edit
        );

        buttons.appendChild(
            remove
        );


        card.appendChild(
            heading
        );

        card.appendChild(
            course
        );

        card.appendChild(
            topic
        );

        card.appendChild(
            preview
        );

        card.appendChild(
            buttons
        );


        list.appendChild(
            card
        );

    });

}


/* =====================================================
   EDIT NOTE
===================================================== */

function editNote(note){

    currentNoteId =
        note.id;


    document.getElementById(
        "course"
    ).value =
        note.course;


    document.getElementById(
        "course"
    ).dispatchEvent(
        new Event("change")
    );


    document.getElementById(
        "topic"
    ).value =
        note.topic;


    document.getElementById(
        "title"
    ).value =
        note.title;


    const stage =
        document.getElementById(
            "editorStage"
        );


    const writing =
        document.getElementById(
            "writingArea"
        );


    const objects =
        document.getElementById(
            "objectsLayer"
        );


    writing.innerHTML =
        "";


    objects.innerHTML =
        "";


    /*
        If the saved note is our canvas,
        reconstruct it.
    */

    const temporary =
        document.createElement("div");


    temporary.innerHTML =
        note.content || "";


    const canvas =
        temporary.querySelector(
            ".ogcons-note-canvas"
        );


    if(canvas){

        /*
            Restore the manually chosen
            editor height.
        */

        const savedHeight =
            parseInt(
                canvas.style.height
            );


        if(
            savedHeight &&
            !isNaN(savedHeight)
        ){

            stage.style.height =
                savedHeight + "px";

        }else{

            stage.style.height =
                "700px";

        }


        const savedWriting =
            canvas.querySelector(
                ".ogcons-writing-layer"
            );


        const savedObjects =
            canvas.querySelector(
                ".ogcons-objects-layer"
            );


        if(savedWriting){

            writing.innerHTML =
                savedWriting.innerHTML;

        }


        if(savedObjects){

            Array.from(
                savedObjects.children
            ).forEach(function(child){

                const clone =
                    child.cloneNode(true);


                clone
                    .querySelectorAll(
                        ".object-controls,.resize-handle,.rotate-handle"
                    )
                    .forEach(function(el){

                        el.remove();

                    });


                objects.appendChild(
                    clone
                );


                makeObjectInteractive(
                    clone
                );

            });

        }

    }else{

        /*
            Old notes without canvas.
        */

        stage.style.height =
            "700px";


        writing.innerHTML =
            note.content || "";

    }


    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });


    showStatus(
        "Note loaded for editing.",
        "success"
    );

}


/* =====================================================
   DELETE NOTE
===================================================== */

async function deleteNote(id){

    const confirmDelete =
        confirm(
            "Are you sure you want to delete this note?"
        );


    if(!confirmDelete)
        return;


    const result =
        await supabaseClient
            .from("notes")
            .delete()
            .eq(
                "id",
                id
            );


    if(result.error){

        showStatus(
            result.error.message,
            "error"
        );

        return;

    }


    if(
        currentNoteId === id
    ){

        clearEditor();

    }


    showStatus(
        "Note deleted successfully.",
        "success"
    );


    loadNotes();

}


/* =====================================================
   CLEAR EDITOR
===================================================== */

function clearEditor(){

    currentNoteId =
        null;


    document.getElementById(
        "course"
    ).value =
        "";


    document.getElementById(
        "topic"
    ).innerHTML =
        '<option value="">Select Topic</option>';


    document.getElementById(
        "title"
    ).value =
        "";


    document.getElementById(
        "writingArea"
    ).innerHTML =
        "";


    document.getElementById(
        "objectsLayer"
    ).innerHTML =
        "";


    /*
        Return to normal starting height.
    */

    document.getElementById(
        "editorStage"
    ).style.height =
        "700px";


    selectedObject =
        null;

}


/* =====================================================
   SEARCH
===================================================== */

function clearSearch(){

    document.getElementById(
        "searchInput"
    ).value =
        "";


    loadNotes();

}


/* =====================================================
   STATUS
===================================================== */

function showStatus(
    message,
    type
){

    const status =
        document.getElementById(
            "status"
        );


    status.textContent =
        message;


    status.className =
        "status " +
        type;


    setTimeout(
        function(){

            status.className =
                "status";

        },
        4000
    );

}


/* =====================================================
   ESCAPE HTML
===================================================== */

function escapeHTML(value){

    return String(value || "")
        .replace(
            /&/g,
            "&amp;"
        )
        .replace(
            /</g,
            "&lt;"
        )
        .replace(
            />/g,
            "&gt;"
        )
        .replace(
            /"/g,
            "&quot;"
        )
        .replace(
            /'/g,
            "&#039;"
        );

}


/* =====================================================
   PREVIEW
===================================================== */

function previewNote(){

    const content =
        prepareHTMLForSaving();


    if(!content){

        alert(
            "There is nothing to preview."
        );

        return;

    }


    document.getElementById(
        "previewInner"
    ).innerHTML =
        content;


    document.getElementById(
        "previewBox"
    ).style.display =
        "block";

}


function closePreview(){

    document.getElementById(
        "previewBox"
    ).style.display =
        "none";

}


/* =====================================================
   START
===================================================== */

loadNotes();

</script>

</body>
</html>
