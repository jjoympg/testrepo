# testrepo
testrepo

#hello world!

#I love GIT!

---

# test 
- name: "test.1 | Remediate | Ensure root level SSH is disabled"
  when:
    - nameOS9_rule_9_1
  tags:
    - level1-server
    - level1-workstation
    - remediate
    - rule_9.1
    - user_accounts
    - NIST800-53R5_IA-5
#