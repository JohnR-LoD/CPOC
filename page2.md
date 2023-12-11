---
title: Manipulate stuff
lab_id: cue-stuff-001-a
type: instruction
exam: stuff
topic: files
question_id: 001
variant: a
primary_lo: [' ']
supporting_lo: [' ', ' ']
nodes_used: ['warty', 'artful']
---

Here's where the instruction content exists.

1. Do something `stuff.txt`
2. Do something else `stuff_sorted.txt`.
3. Do the last thing (e.g., `stuff`).

---
type: lab-stuff
node: note1
---

function grade-stuff-001-a-01 {
    grep -E stuff 
    pass-check
}


function grade-stuff-001-a-02 {
    sort stuff
}


function grade-stuff-001-a-03 {
    stuff
    if stuff; then
        pass-check
    else
        fail-check
    fi
}


function grade-stuff-001-a-04 {
    if [ -stuff ]; then
        pass-check
    else
        fail-check
    fi
}


---
type: stuff-provisioning
node: node1
---

### cue-stuff-001-a
        cat <<EOF > stuff
EOF
        ;;


---
type: labstuff-resolution
node: node1
---

### cue-stuff-001-a
        grep -E stuff
        ;;
