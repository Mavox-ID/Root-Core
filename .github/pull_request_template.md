# Pull Request

## Summary

Briefly describe the purpose of this pull request.

Example:

* Fix kernel panic during boot on legacy hardware
* Improve filesystem mount validation
* Add command parser refactor

---

## Type of Change

Please mark relevant items:

* [ ] Bug fix
* [ ] New feature
* [ ] Performance improvement
* [ ] Refactor
* [ ] Documentation update
* [ ] Security improvement
* [ ] Build / CI update

---

## What Changed

Describe the actual changes made.

* Updated scheduler lock handling
* Added null pointer checks
* Reworked disk detection flow

---

## Why This Change Is Needed

Explain the problem being solved or value added.

---

## Testing Performed

Describe how this was tested.

* [ ] Builds successfully
* [ ] Boots in QEMU
* [ ] Tested on real hardware
* [ ] Unit tests passed
* [ ] Regression checked

Additional notes:

```text
Booted on x86_64 QEMU with 256MB RAM.
Filesystem operations verified.
```

---

## Breaking Changes

* [ ] No breaking changes
* [ ] Yes (describe below)

If yes, explain compatibility impact.

---

## Security Impact

* [ ] No known security impact
* [ ] Security relevant change

If relevant, explain briefly.

---

## Checklist

* [ ] Code follows project style
* [ ] Self-review completed
* [ ] Documentation updated if needed
* [ ] No unrelated changes included
* [ ] Commit messages are clean
* [ ] Ready for review

---

## Required in Root Core (If you don't know how to help, this checklist is for you)

* [ ] Create more verification tests at the beginning of the test.
* [ ] Add more commands according to the CROCI standard.
* [ ] Create support for USB and disks in /usb, and also their configuration via the di (disk info) command.
* [ ] Add an internet driver (Wi-Fi + Ethernet) and a command for managing according to the CROCI standard (wire)
* [ ] (If there is an internet option!) Create a package manager
* [ ] Create a working Bash and .bash scripts

---

## Additional Notes

Anything reviewers should know.
