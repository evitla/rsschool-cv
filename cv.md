# Curriculum vitae

### About me
My name is Dinmukhamed Sailaubek. I've been teaching theoretical physics at the university since 2017, after graduating from my master degree. Also I work in a small research team and I'm looking for a role where I can grow and continue to learn from other experienced team members.

### Contact
**Phone:** [+7 (708) 623-32-06](tel:+77086233206)

**E-mail:** [s.dinmuhamed@gmail.com](mailto:s.dinmuhamed@gmail.com)

### Skills
<table border="0">
  <tr>
    <td><b>Latex</b></td>
    <td><img src="https://progress-bar.dev/85/?suffix"></td>
  </tr>
  <tr>
    <td><b>Python</b></td>
    <td><img src="https://progress-bar.dev/80/?suffix"></td>
  </tr>
  <tr>
    <td><b>HTML</b></td>
    <td><img src="https://progress-bar.dev/70/?suffix"></td>
  </tr>
  <tr>
    <td><b>CSS</b></td>
    <td><img src="https://progress-bar.dev/60/?suffix"></td>
  </tr>
  <tr>
    <td><b>JavaScript</b></td>
    <td><img src="https://progress-bar.dev/55/?suffix"></td>
  </tr>
  <tr>
    <td><b>Git</b></td>
    <td><img src="https://progress-bar.dev/50/?suffix"></td>
  </tr>
  <tr>
    <td><b>C++</b></td>
    <td><img src="https://progress-bar.dev/50/?suffix"></td>
  </tr>
  <tr>
    <td><b>English</b></td>
    <td>A2</td>
  </tr>
</table>

### Code example
```python
import re

def validate_user(username, minlen):
    """Checks if the received username matches the required conditions."""
    if type(username) != str:
        raise TypeError("username must be a string")
    if minlen < 1:
        raise ValueError("minlen must be at least 1")
    
    # Usernames can't be shorter than minlen
    if len(username) < minlen:
        return False
    # Usernames can only use letters, numbers, dots and underscores
    if not re.match('^[a-z0-9._]*$', username):
        return False
    # Usernames can't begin with a number
    if username[0].isnumeric():
        return False
    return True
```

### Experience

### Education
**Lomonosov Moscow State University**, master of Physics

**Online Courses**:
* [Deep Learning](https://coursera.org/share/14063aa1f6c7abb25be15d55189681c9)
* [Python for Everybody](https://coursera.org/share/d9a2a3350c04671b425001bb38486941)
* [Google IT Automation with Python](https://coursera.org/share/a56e6265c6abd4c0295bdab430f1df90)
