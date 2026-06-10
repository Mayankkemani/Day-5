# Day 05 – Linux Package Management & Python For Loop 🚀

## Linux Learning 🐧

### Package Management with APT

Today I learned how Ubuntu manages software using the APT Package Manager.

### Commands Practiced

#### Check APT Version

```bash
apt --version
```

#### Update Package List

```bash
sudo apt update
```

Purpose:

```text
Download latest package information from repositories.
```

#### Install Packages

```bash
sudo apt install nginx -y
sudo apt install git -y
sudo apt install curl -y
```

#### Verify Installation

```bash
git --version
curl --version
```

#### Remove Package

```bash
sudo apt remove nginx
```

#### Remove Package + Configuration

```bash
sudo apt purge nginx
```

---

## Key Linux Learning

```text
apt update  → Update package list
apt install → Install software
apt remove  → Remove software
apt purge   → Remove software + configuration files
```

---

# Python Learning 🐍

## Topics Covered

### Comparison Operators

```python
==
!=
>
<
>=
<=
```

Examples:

```python
x = 10

print(x == 10)
print(x != 5)
print(x > 5)
print(x < 5)
```

---

## if-else

Example:

```python
age = 17

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
```

---

## FOR Loop

### Basic Loop

```python
for i in range(5):
    print(i)
```

Output:

```text
0
1
2
3
4
```

### Start and Stop

```python
for i in range(1,6):
    print(i)
```

Output:

```text
1
2
3
4
5
```

### Step Value

```python
for i in range(2,11,2):
    print(i)
```

Output:

```text
2
4
6
8
10
```

### Reverse Loop

```python
for i in range(10,0,-1):
    print(i)
```

Output:

```text
10
9
8
7
6
5
4
3
2
1
```

---

## Key Python Learning

```text
range(stop)
range(start, stop)
range(start, stop, step)

Start value included
Stop value not included
```

---

# Skills Learned Today

✅ Linux Package Management
✅ apt update
✅ apt install
✅ apt remove
✅ apt purge
✅ Nginx Installation
✅ Curl Installation
✅ Comparison Operators
✅ True / False Logic
✅ if-else Statements
✅ FOR Loop
✅ Reverse Loop
✅ Step Values in range()

---

# Learning Summary

Today I learned how software is managed in Ubuntu using APT and strengthened my Python fundamentals with comparison operators, if-else statements, and for loops.

Roadmap:

Linux → Python → Git → AWS → Docker → Kubernetes → DevOps 🚀
