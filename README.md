# README

## LOG

Creating the following folder structure:

```
teach/
├── shared/
│   ├── images/
│   ├── logos/
│   ├── memes/
│   └── gifs/
│
└── BLOCK-MASTER/
    ├── W1/
    │   ├── S1/
    │   │   ├── W1S1-1.md    # Week 1 Session 1
    │   │   ├── W1S1-2.md    # Week 1 Session 2
    │   │   ├── W1S1-3.md    # Week 1 Session 3
    │   │   ├── W1S1-4.md    # Week 1 Session 4
    │   │   └── W1S1-5.md    # Week 1 Session 5
    │   ├── S2/
    │   │   ├── . . .
    │   ├── S3/
    │   │   ├── . . .
    │   ├── S4/
    │   │   ├── . . .
    │   └── S5/
    │   │   ├── . . .
    │
    ├── W2/
    │   ├── S1/ . . .
    │   ├── S2/ . . .
    │   ├── S3/ . . .
    │   ├── S4/ . . .
    │   └── S5/ . . .
    │
    ├── W3/ . . .     │
    ├── W4/ . . .     │
    └── W5/ . . .
```

Command:

```shell
# Create shared folders
mkdir -p shared/{images,logos,memes,gifs}

# Create BLOCK-MASTER structure and Marp files
for W in {1..5}; do
  WEEK_DIR="BLOCK-MASTER/W${W}"
  mkdir -p "$WEEK_DIR"

  for S in {1..5}; do
    SESSION_DIR="$WEEK_DIR/S${S}"
    mkdir -p "$SESSION_DIR"

    for N in {1..5}; do
      FILE="$SESSION_DIR/W${W}S${S}-${N}.md"
      cat > "$FILE" <<EOF
---
marp: true
header: "University of Greater Manchester"
footer: "CODE: TITLE"
paginate: true
theme: ugm
size: 16:9
---

<!-- _class: title -->

# HEADING

## SUBHEADING

**Week ${W}: Session ${S}-${N}**

---
EOF
    done
  done
done

```
