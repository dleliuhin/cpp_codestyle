# Code style configuration file

---

## 1. Description

Based on [readability* group](https://clang.llvm.org/extra/clang-tidy/checks/list.html) of CLang-Tidy Checks.

---

## 2. Usage

1. Fork repo

2. Add new check arg to ```Checks``` group.

3. Write each arg option in ```CheckOptions``` group with specific ```- key: ...``` and ```value: ...```.

4. File is callable from **service_template** *codestyle.sh* script.

5. Output is list of warnings.

*Note:* If no sources warnings, may be display warnings from submodules.

---
## 3. Release History

| Version | Type    | ChangeLog                                      |
|---------|---------|------------------------------------------------|
| 1.0     | Feature | Initial commit. Basic readability options add. |

---
## 4. Support

Reach out to me at one of the following places!

- Telegram at - <a href="http://https://telegram.org" target="_blank">`@DLeliuhin`</a>
- Email at - dleliuhin@gmail.com.
---

**JSC NIIAS**