<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: ansible-role-rhel_8_cis
DEPRECATED: Use trippsc2.cis.rhel8 instead.

## Requirements

| Platform | Versions |
| -------- | -------- |
| EL | <ul><li>8</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.posix |
| community.general |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| rhel8cis_skip_reboot | Whether to skip the reboot step. | bool | no |  | true |
| rhel8cis_level | The CIS benchmark level to apply. | int | no | <ul><li>1</li><li>2</li></ul> | 2 |
| rhel8cis_machine_type | The type of machine for which to apply the CIS benchmarks. | str | no | <ul><li>server</li><li>workstation</li></ul> | server |
| rhel8cis_rule_1_1_1_1_enabled | Whether to apply CIS rule 1.1.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_2_enabled | Whether to apply CIS rule 1.1.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_3_enabled | Whether to apply CIS rule 1.1.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_4_enabled | Whether to apply CIS rule 1.1.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_5_enabled | Whether to apply CIS rule 1.1.1.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_6_enabled | Whether to apply CIS rule 1.1.1.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_7_enabled | Whether to apply CIS rule 1.1.1.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_8_enabled | Whether to apply CIS rule 1.1.1.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_1_1_enabled | Whether to apply CIS rule 1.1.2.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_1_2_enabled | Whether to apply CIS rule 1.1.2.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_1_3_enabled | Whether to apply CIS rule 1.1.2.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_1_4_enabled | Whether to apply CIS rule 1.1.2.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_2_1_enabled | Whether to apply CIS rule 1.1.2.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_2_2_enabled | Whether to apply CIS rule 1.1.2.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_2_3_enabled | Whether to apply CIS rule 1.1.2.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_2_4_enabled | Whether to apply CIS rule 1.1.2.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_3_1_enabled | Whether to apply CIS rule 1.1.2.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_3_2_enabled | Whether to apply CIS rule 1.1.2.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_3_3_enabled | Whether to apply CIS rule 1.1.2.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_4_1_enabled | Whether to apply CIS rule 1.1.2.4.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_4_2_enabled | Whether to apply CIS rule 1.1.2.4.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_4_3_enabled | Whether to apply CIS rule 1.1.2.4.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_5_1_enabled | Whether to apply CIS rule 1.1.2.5.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_5_2_enabled | Whether to apply CIS rule 1.1.2.5.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_5_3_enabled | Whether to apply CIS rule 1.1.2.5.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_5_4_enabled | Whether to apply CIS rule 1.1.2.5.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_6_1_enabled | Whether to apply CIS rule 1.1.2.6.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_6_2_enabled | Whether to apply CIS rule 1.1.2.6.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_6_3_enabled | Whether to apply CIS rule 1.1.2.6.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_6_4_enabled | Whether to apply CIS rule 1.1.2.6.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_7_1_enabled | Whether to apply CIS rule 1.1.2.7.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_7_2_enabled | Whether to apply CIS rule 1.1.2.7.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_7_3_enabled | Whether to apply CIS rule 1.1.2.7.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_2_7_4_enabled | Whether to apply CIS rule 1.1.2.7.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_2_1_enabled | Whether to apply CIS rule 1.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_2_2_enabled | Whether to apply CIS rule 1.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_2_3_enabled | Whether to apply CIS rule 1.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_2_4_enabled | Whether to apply CIS rule 1.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_2_5_enabled | Whether to apply CIS rule 1.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_3_1_enabled | Whether to apply CIS rule 1.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_3_2_enabled | Whether to apply CIS rule 1.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_4_1_enabled | Whether to apply CIS rule 1.4.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_4_2_enabled | Whether to apply CIS rule 1.4.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_4_3_enabled | Whether to apply CIS rule 1.4.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_4_4_enabled | Whether to apply CIS rule 1.4.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_1_enabled | Whether to apply CIS rule 1.5.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_2_enabled | Whether to apply CIS rule 1.5.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_3_enabled | Whether to apply CIS rule 1.5.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_4_enabled | Whether to apply CIS rule 1.5.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_5_enabled | Whether to apply CIS rule 1.5.1.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_6_enabled | Whether to apply CIS rule 1.5.1.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_7_enabled | Whether to apply CIS rule 1.5.1.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_5_1_8_enabled | Whether to apply CIS rule 1.5.1.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_6_1_enabled | Whether to apply CIS rule 1.6.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_6_2_enabled | Whether to apply CIS rule 1.6.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_6_3_enabled | Whether to apply CIS rule 1.6.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_6_4_enabled | Whether to apply CIS rule 1.6.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_1_enabled | Whether to apply CIS rule 1.7.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_2_enabled | Whether to apply CIS rule 1.7.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_3_enabled | Whether to apply CIS rule 1.7.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_4_enabled | Whether to apply CIS rule 1.7.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_5_enabled | Whether to apply CIS rule 1.7.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_7_6_enabled | Whether to apply CIS rule 1.7.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_1_enabled | Whether to apply CIS rule 1.8.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_2_enabled | Whether to apply CIS rule 1.8.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_3_enabled | Whether to apply CIS rule 1.8.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_4_enabled | Whether to apply CIS rule 1.8.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_5_enabled | Whether to apply CIS rule 1.8.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_6_enabled | Whether to apply CIS rule 1.8.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_7_enabled | Whether to apply CIS rule 1.8.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_8_enabled | Whether to apply CIS rule 1.8.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_9_enabled | Whether to apply CIS rule 1.8.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_8_10_enabled | Whether to apply CIS rule 1.8.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_1_1_enabled | Whether to apply CIS rule 2.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_1_2_enabled | Whether to apply CIS rule 2.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_1_3_enabled | Whether to apply CIS rule 2.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_1_enabled | Whether to apply CIS rule 2.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_2_enabled | Whether to apply CIS rule 2.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_3_enabled | Whether to apply CIS rule 2.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_4_enabled | Whether to apply CIS rule 2.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_5_enabled | Whether to apply CIS rule 2.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_6_enabled | Whether to apply CIS rule 2.2.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_7_enabled | Whether to apply CIS rule 2.2.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_8_enabled | Whether to apply CIS rule 2.2.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_9_enabled | Whether to apply CIS rule 2.2.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_10_enabled | Whether to apply CIS rule 2.2.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_11_enabled | Whether to apply CIS rule 2.2.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_12_enabled | Whether to apply CIS rule 2.2.12. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_13_enabled | Whether to apply CIS rule 2.2.13. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_14_enabled | Whether to apply CIS rule 2.2.14. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_15_enabled | Whether to apply CIS rule 2.2.15. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_16_enabled | Whether to apply CIS rule 2.2.16. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_17_enabled | Whether to apply CIS rule 2.2.17. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_18_enabled | Whether to apply CIS rule 2.2.18. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_19_enabled | Whether to apply CIS rule 2.2.19. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_20_enabled | Whether to apply CIS rule 2.2.20. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_21_enabled | Whether to apply CIS rule 2.2.21. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_2_22_enabled | Whether to apply CIS rule 2.2.22. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_3_1_enabled | Whether to apply CIS rule 2.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_3_2_enabled | Whether to apply CIS rule 2.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_3_3_enabled | Whether to apply CIS rule 2.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_3_4_enabled | Whether to apply CIS rule 2.3.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_2_3_5_enabled | Whether to apply CIS rule 2.3.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_1_1_enabled | Whether to apply CIS rule 3.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_1_2_enabled | Whether to apply CIS rule 3.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_1_3_enabled | Whether to apply CIS rule 3.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_2_1_enabled | Whether to apply CIS rule 3.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_2_2_enabled | Whether to apply CIS rule 3.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_2_3_enabled | Whether to apply CIS rule 3.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_2_4_enabled | Whether to apply CIS rule 3.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_1_enabled | Whether to apply CIS rule 3.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_2_enabled | Whether to apply CIS rule 3.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_3_enabled | Whether to apply CIS rule 3.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_4_enabled | Whether to apply CIS rule 3.3.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_5_enabled | Whether to apply CIS rule 3.3.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_6_enabled | Whether to apply CIS rule 3.3.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_7_enabled | Whether to apply CIS rule 3.3.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_8_enabled | Whether to apply CIS rule 3.3.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_9_enabled | Whether to apply CIS rule 3.3.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_10_enabled | Whether to apply CIS rule 3.3.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_3_11_enabled | Whether to apply CIS rule 3.3.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_1_1_enabled | Whether to apply CIS rule 3.4.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_1_2_enabled | Whether to apply CIS rule 3.4.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_2_1_enabled | Whether to apply CIS rule 3.4.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_2_2_enabled | Whether to apply CIS rule 3.4.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_2_3_enabled | Whether to apply CIS rule 3.4.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_2_4_enabled | Whether to apply CIS rule 3.4.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_3_4_2_5_enabled | Whether to apply CIS rule 3.4.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_1_enabled | Whether to apply CIS rule 4.1.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_2_enabled | Whether to apply CIS rule 4.1.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_3_enabled | Whether to apply CIS rule 4.1.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_4_enabled | Whether to apply CIS rule 4.1.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_5_enabled | Whether to apply CIS rule 4.1.1.5. This applies when the level and machine type are appropriate. | str | no |  |  |
| rhel8cis_rule_4_1_1_6_enabled | Whether to apply CIS rule 4.1.1.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_7_enabled | Whether to apply CIS rule 4.1.1.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_1_8_enabled | Whether to apply CIS rule 4.1.1.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_1_2_1_enabled | Whether to apply CIS rule 4.1.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_1_enabled | Whether to apply CIS rule 4.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_2_enabled | Whether to apply CIS rule 4.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_3_enabled | Whether to apply CIS rule 4.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_4_enabled | Whether to apply CIS rule 4.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_5_enabled | Whether to apply CIS rule 4.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_6_enabled | Whether to apply CIS rule 4.2.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_7_enabled | Whether to apply CIS rule 4.2.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_8_enabled | Whether to apply CIS rule 4.2.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_9_enabled | Whether to apply CIS rule 4.2.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_10_enabled | Whether to apply CIS rule 4.2.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_11_enabled | Whether to apply CIS rule 4.2.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_12_enabled | Whether to apply CIS rule 4.2.12. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_13_enabled | Whether to apply CIS rule 4.2.13. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_14_enabled | Whether to apply CIS rule 4.2.14. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_15_enabled | Whether to apply CIS rule 4.2.15. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_16_enabled | Whether to apply CIS rule 4.2.16. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_17_enabled | Whether to apply CIS rule 4.2.17. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_18_enabled | Whether to apply CIS rule 4.2.18. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_19_enabled | Whether to apply CIS rule 4.2.19. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_20_enabled | Whether to apply CIS rule 4.2.20. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_21_enabled | Whether to apply CIS rule 4.2.21. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_2_22_enabled | Whether to apply CIS rule 4.2.22. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_1_enabled | Whether to apply CIS rule 4.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_2_enabled | Whether to apply CIS rule 4.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_3_enabled | Whether to apply CIS rule 4.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_4_enabled | Whether to apply CIS rule 4.3.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_5_enabled | Whether to apply CIS rule 4.3.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_6_enabled | Whether to apply CIS rule 4.3.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_3_7_enabled | Whether to apply CIS rule 4.3.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_1_1_enabled | Whether to apply CIS rule 4.4.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_1_2_enabled | Whether to apply CIS rule 4.4.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_2_1_enabled | Whether to apply CIS rule 4.4.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_2_2_enabled | Whether to apply CIS rule 4.4.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_2_3_enabled | Whether to apply CIS rule 4.4.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_2_4_enabled | Whether to apply CIS rule 4.4.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_2_5_enabled | Whether to apply CIS rule 4.4.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_1_1_enabled | Whether to apply CIS rule 4.4.3.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_1_2_enabled | Whether to apply CIS rule 4.4.3.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_1_3_enabled | Whether to apply CIS rule 4.4.3.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_1_enabled | Whether to apply CIS rule 4.4.3.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_2_enabled | Whether to apply CIS rule 4.4.3.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_3_enabled | Whether to apply CIS rule 4.4.3.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_4_enabled | Whether to apply CIS rule 4.4.3.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_5_enabled | Whether to apply CIS rule 4.4.3.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_6_enabled | Whether to apply CIS rule 4.4.3.2.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_2_7_enabled | Whether to apply CIS rule 4.4.3.2.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_3_1_enabled | Whether to apply CIS rule 4.4.3.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_3_2_enabled | Whether to apply CIS rule 4.4.3.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_3_3_enabled | Whether to apply CIS rule 4.4.3.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_4_1_enabled | Whether to apply CIS rule 4.4.3.4.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_4_2_enabled | Whether to apply CIS rule 4.4.3.4.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_4_3_enabled | Whether to apply CIS rule 4.4.3.4.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_4_3_4_4_enabled | Whether to apply CIS rule 4.4.3.4.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_1_1_enabled | Whether to apply CIS rule 4.5.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_1_2_enabled | Whether to apply CIS rule 4.5.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_1_3_enabled | Whether to apply CIS rule 4.5.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_1_4_enabled | Whether to apply CIS rule 4.5.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_1_5_enabled | Whether to apply CIS rule 4.5.1.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_2_1_enabled | Whether to apply CIS rule 4.5.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_2_2_enabled | Whether to apply CIS rule 4.5.2.2. This applies when the level and machine type are appropriate. | str | no |  |  |
| rhel8cis_rule_4_5_2_3_enabled | Whether to apply CIS rule 4.5.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_2_4_enabled | Whether to apply CIS rule 4.5.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_3_1_enabled | Whether to apply CIS rule 4.5.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_3_2_enabled | Whether to apply CIS rule 4.5.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_4_5_3_3_enabled | Whether to apply CIS rule 4.5.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_1_enabled | Whether to apply CIS rule 5.1.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_2_enabled | Whether to apply CIS rule 5.1.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_3_enabled | Whether to apply CIS rule 5.1.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_4_enabled | Whether to apply CIS rule 5.1.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_5_enabled | Whether to apply CIS rule 5.1.1.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_6_enabled | Whether to apply CIS rule 5.1.1.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_1_7_enabled | Whether to apply CIS rule 5.1.1.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_1_1_enabled | Whether to apply CIS rule 5.1.2.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_1_2_enabled | Whether to apply CIS rule 5.1.2.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_1_3_enabled | Whether to apply CIS rule 5.1.2.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_1_4_enabled | Whether to apply CIS rule 5.1.2.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_2_enabled | Whether to apply CIS rule 5.1.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_3_enabled | Whether to apply CIS rule 5.1.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_4_enabled | Whether to apply CIS rule 5.1.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_5_enabled | Whether to apply CIS rule 5.1.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_2_6_enabled | Whether to apply CIS rule 5.1.2.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_3_enabled | Whether to apply CIS rule 5.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_1_4_enabled | Whether to apply CIS rule 5.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_1_1_enabled | Whether to apply CIS rule 5.2.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_1_2_enabled | Whether to apply CIS rule 5.2.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_1_3_enabled | Whether to apply CIS rule 5.2.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_1_4_enabled | Whether to apply CIS rule 5.2.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_2_1_enabled | Whether to apply CIS rule 5.2.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_2_2_enabled | Whether to apply CIS rule 5.2.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_2_3_enabled | Whether to apply CIS rule 5.2.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_2_4_enabled | Whether to apply CIS rule 5.2.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_1_enabled | Whether to apply CIS rule 5.2.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_2_enabled | Whether to apply CIS rule 5.2.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_3_enabled | Whether to apply CIS rule 5.2.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_4_enabled | Whether to apply CIS rule 5.2.3.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_5_enabled | Whether to apply CIS rule 5.2.3.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_6_enabled | Whether to apply CIS rule 5.2.3.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_7_enabled | Whether to apply CIS rule 5.2.3.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_8_enabled | Whether to apply CIS rule 5.2.3.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_9_enabled | Whether to apply CIS rule 5.2.3.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_10_enabled | Whether to apply CIS rule 5.2.3.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_11_enabled | Whether to apply CIS rule 5.2.3.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_12_enabled | Whether to apply CIS rule 5.2.3.12. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_13_enabled | Whether to apply CIS rule 5.2.3.13. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_14_enabled | Whether to apply CIS rule 5.2.3.14. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_15_enabled | Whether to apply CIS rule 5.2.3.15. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_16_enabled | Whether to apply CIS rule 5.2.3.16. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_17_enabled | Whether to apply CIS rule 5.2.3.17. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_18_enabled | Whether to apply CIS rule 5.2.3.18. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_19_enabled | Whether to apply CIS rule 5.2.3.19. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_20_enabled | Whether to apply CIS rule 5.2.3.20. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_3_21_enabled | Whether to apply CIS rule 5.2.3.21. This applies when the level and machine type are appropriate. | str | no |  |  |
| rhel8cis_rule_5_2_4_1_enabled | Whether to apply CIS rule 5.2.4.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_2_enabled | Whether to apply CIS rule 5.2.4.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_3_enabled | Whether to apply CIS rule 5.2.4.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_4_enabled | Whether to apply CIS rule 5.2.4.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_5_enabled | Whether to apply CIS rule 5.2.4.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_6_enabled | Whether to apply CIS rule 5.2.4.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_7_enabled | Whether to apply CIS rule 5.2.4.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_8_enabled | Whether to apply CIS rule 5.2.4.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_9_enabled | Whether to apply CIS rule 5.2.4.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_2_4_10_enabled | Whether to apply CIS rule 5.2.4.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_3_1_enabled | Whether to apply CIS rule 5.3.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_3_2_enabled | Whether to apply CIS rule 5.3.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_5_3_3_enabled | Whether to apply CIS rule 5.3.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_1_enabled | Whether to apply CIS rule 6.1.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_2_enabled | Whether to apply CIS rule 6.1.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_3_enabled | Whether to apply CIS rule 6.1.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_4_enabled | Whether to apply CIS rule 6.1.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_5_enabled | Whether to apply CIS rule 6.1.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_6_enabled | Whether to apply CIS rule 6.1.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_7_enabled | Whether to apply CIS rule 6.1.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_8_enabled | Whether to apply CIS rule 6.1.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_9_enabled | Whether to apply CIS rule 6.1.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_10_enabled | Whether to apply CIS rule 6.1.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_11_enabled | Whether to apply CIS rule 6.1.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_12_enabled | Whether to apply CIS rule 6.1.12. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_13_enabled | Whether to apply CIS rule 6.1.13. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_1_14_enabled | Whether to apply CIS rule 6.1.14. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_1_enabled | Whether to apply CIS rule 6.2.1. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_2_enabled | Whether to apply CIS rule 6.2.2. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_3_enabled | Whether to apply CIS rule 6.2.3. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_4_enabled | Whether to apply CIS rule 6.2.4. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_5_enabled | Whether to apply CIS rule 6.2.5. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_6_enabled | Whether to apply CIS rule 6.2.6. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_7_enabled | Whether to apply CIS rule 6.2.7. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_8_enabled | Whether to apply CIS rule 6.2.8. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_9_enabled | Whether to apply CIS rule 6.2.9. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_10_enabled | Whether to apply CIS rule 6.2.10. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_6_2_11_enabled | Whether to apply CIS rule 6.2.11. This applies when the level and machine type are appropriate. | bool | no |  | true |
| rhel8cis_rule_1_1_1_6_force | Whether to override the level requirement for CIS rule 1.1.1.6. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_1_7_force | Whether to override the level requirement for CIS rule 1.1.1.7. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_1_8_force | Whether to override the level requirement for CIS rule 1.1.1.8. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_2_3_1_force | Whether to override the level requirement for CIS rule 1.1.2.3.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_2_4_1_force | Whether to override the level requirement for CIS rule 1.1.2.4.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_2_5_1_force | Whether to override the level requirement for CIS rule 1.1.2.5.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_2_6_1_force | Whether to override the level requirement for CIS rule 1.1.2.6.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_1_2_7_1_force | Whether to override the level requirement for CIS rule 1.1.2.7.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_2_3_force | Whether to override the level requirement for CIS rule 1.2.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_5_1_5_force | Whether to override the level requirement for CIS rule 1.5.1.5. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_8_1_force | Whether to override the level requirement for CIS rule 1.8.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_8_6_force | Whether to override the level requirement for CIS rule 1.8.6. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_1_8_7_force | Whether to override the level requirement for CIS rule 1.8.7. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_2_2_1_force | Whether to override the level requirement for CIS rule 2.2.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_2_2_2_force | Whether to override the level requirement for CIS rule 2.2.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_2_2_20_force | Whether to override the level requirement for CIS rule 2.2.20. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_2_3_2_force | Whether to override the level requirement for CIS rule 2.3.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_3_1_3_force | Whether to override the level requirement for CIS rule 3.1.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_3_2_1_force | Whether to override the level requirement for CIS rule 3.2.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_3_2_2_force | Whether to override the level requirement for CIS rule 3.2.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_3_2_3_force | Whether to override the level requirement for CIS rule 3.2.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_3_2_4_force | Whether to override the level requirement for CIS rule 3.2.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_4_2_8_force | Whether to override the level requirement for CIS rule 4.2.8. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_4_3_4_force | Whether to override the level requirement for CIS rule 4.3.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_4_4_3_1_3_force | Whether to override the level requirement for CIS rule 4.4.3.1.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_4_5_3_1_force | Whether to override the level requirement for CIS rule 4.5.3.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_1_1_force | Whether to override the level requirement for CIS rule 5.2.1.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_1_2_force | Whether to override the level requirement for CIS rule 5.2.1.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_1_3_force | Whether to override the level requirement for CIS rule 5.2.1.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_1_4_force | Whether to override the level requirement for CIS rule 5.2.1.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_2_1_force | Whether to override the level requirement for CIS rule 5.2.2.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_2_2_force | Whether to override the level requirement for CIS rule 5.2.2.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_2_3_force | Whether to override the level requirement for CIS rule 5.2.2.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_2_4_force | Whether to override the level requirement for CIS rule 5.2.2.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_1_force | Whether to override the level requirement for CIS rule 5.2.3.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_2_force | Whether to override the level requirement for CIS rule 5.2.3.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_3_force | Whether to override the level requirement for CIS rule 5.2.3.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_4_force | Whether to override the level requirement for CIS rule 5.2.3.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_5_force | Whether to override the level requirement for CIS rule 5.2.3.5. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_6_force | Whether to override the level requirement for CIS rule 5.2.3.6. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_7_force | Whether to override the level requirement for CIS rule 5.2.3.7. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_8_force | Whether to override the level requirement for CIS rule 5.2.3.8. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_9_force | Whether to override the level requirement for CIS rule 5.2.3.9. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_10_force | Whether to override the level requirement for CIS rule 5.2.3.10. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_11_force | Whether to override the level requirement for CIS rule 5.2.3.11. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_12_force | Whether to override the level requirement for CIS rule 5.2.3.12. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_13_force | Whether to override the level requirement for CIS rule 5.2.3.13. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_14_force | Whether to override the level requirement for CIS rule 5.2.3.14. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_15_force | Whether to override the level requirement for CIS rule 5.2.3.15. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_16_force | Whether to override the level requirement for CIS rule 5.2.3.16. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_17_force | Whether to override the level requirement for CIS rule 5.2.3.17. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_18_force | Whether to override the level requirement for CIS rule 5.2.3.18. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_19_force | Whether to override the level requirement for CIS rule 5.2.3.19. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_20_force | Whether to override the level requirement for CIS rule 5.2.3.20. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_3_21_force | Whether to override the level requirement for CIS rule 5.2.3.21. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_1_force | Whether to override the level requirement for CIS rule 5.2.4.1. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_2_force | Whether to override the level requirement for CIS rule 5.2.4.2. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_3_force | Whether to override the level requirement for CIS rule 5.2.4.3. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_4_force | Whether to override the level requirement for CIS rule 5.2.4.4. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_5_force | Whether to override the level requirement for CIS rule 5.2.4.5. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_6_force | Whether to override the level requirement for CIS rule 5.2.4.6. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_7_force | Whether to override the level requirement for CIS rule 5.2.4.7. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_8_force | Whether to override the level requirement for CIS rule 5.2.4.8. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_9_force | Whether to override the level requirement for CIS rule 5.2.4.9. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_5_2_4_10_force | Whether to override the level requirement for CIS rule 5.2.4.10. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_rule_6_1_14_force | Whether to override the level requirement for CIS rule 6.1.14. This applies when the machine type is appropriate. | bool | no |  | false |
| rhel8cis_tmp_mount_opts | The mount options for the /tmp partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid", "noexec"] |
| rhel8cis_dev_shm_mount_opts | The mount options for the /dev/shm partition. | list of 'str' | no |  | ["mode=1777", "strictatime", "nodev", "nosuid", "noexec"] |
| rhel8cis_home_mount_opts | The mount options for the /home partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid"] |
| rhel8cis_var_mount_opts | The mount options for the /var partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid"] |
| rhel8cis_var_tmp_mount_opts | The mount options for the /var/tmp partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid", "noexec"] |
| rhel8cis_var_log_mount_opts | The mount options for the /var/log partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid", "noexec"] |
| rhel8cis_var_log_audit_mount_opts | The mount options for the /var/log/audit partition. | list of 'str' | no |  | ["defaults", "nodev", "nosuid", "noexec"] |
| rhel8cis_force_reset_bootloader_password | Whether to force a reset of the bootloader password, even if one is set. Setting this to `true` will make the role not idempotent. | bool | no |  | false |
| rhel8cis_selinux_policy | The SELinux policy to use. | str | no |  | targeted |
| rhel8cis_selinux_mode | The SELinux mode to use. | str | no |  | enforcing |
| rhel8cis_crypto_policy | The crypto policy to use. | str | no |  | DEFAULT |
| rhel8cis_crypto_subpolicies | The crypto subpolicies to use. | list of 'str' | no |  | ["NO-SHA1", "NO-SSHCBC", "NO-WEAKMAC"] |
| rhel8cis_use_motd | Whether to use the Message of the Day (MOTD). | bool | no |  | true |
| rhel8cis_motd_banner | The banner to use for the Message of the Day (MOTD). | str | no |  | Authorized users only.\n\nAll activity may be monitored and reported.\n\n |
| rhel8cis_use_issue | Whether to use the issue file. | bool | no |  | false |
| rhel8cis_issue_banner | The banner to use for the issue file. | str | no |  | Authorized users only.\n\nAll activity may be monitored and reported.\n\n |
| rhel8cis_use_issue_net | Whether to use the issue.net file. | bool | no |  | false |
| rhel8cis_issue_net_banner | The banner to use for the issue.net file. | str | no |  | Authorized users only.\n\nAll activity may be monitored and reported.\n\n |
| rhel8cis_gdm_banner_text | The banner text to use for the GDM login screen. | str | no |  | Authorized users only. All activity may be monitored and reported. |
| rhel8cis_chrony_servers | The NTP server configuration to use with chrony. | list of dicts of 'rhel8cis_chrony_servers' options | no |  | [{"name": "0.pool.ntp.org", "options": ["minpoll 8"]}, {"name": "1.pool.ntp.org", "options": ["minpoll 8"]}, {"name": "2.pool.ntp.org", "options": ["minpoll 8"]}, {"name": "3.pool.ntp.org", "options": ["minpoll 8"]}] |
| rhel8cis_autofs_needed | Whether the `autofs` package is needed. If set to `true`, the `autofs` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_avahi_needed | Whether the `avahi` package is needed. If set to `true`, the `avahi` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_dhcp_server_needed | Whether the `dhcp-server` package is needed. If set to `true`, the `dhcp-server` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_bind_needed | Whether the `bind` package is needed. If set to `true`, the `bind` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_dnsmasq_needed | Whether the `dnsmasq` package is needed. If set to `true`, the `dnsmasq` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_samba_needed | Whether the `samba` package is needed. If set to `true`, the `samba` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_vsftpd_needed | Whether the `vsftpd` package is needed. If set to `true`, the `vsftpd` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_dovecot_needed | Whether the `dovecot` package is needed. If set to `true`, the `dovecot` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_cyrus_imapd_needed | Whether the `cyrus-imapd` package is needed. If set to `true`, the `cyrus-imapd` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_nfs_utils_needed | Whether the `nfs-utils` package is needed. If set to `true`, the `nfs-utils` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_ypserv_needed | Whether the `ypserv` package is needed. If set to `true`, the `ypserv` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_cups_needed | Whether the `cups` package is needed. If set to `true`, the `cups` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_rpcbind_needed | Whether the `rpcbind` package is needed. If set to `true`, the `rpcbind` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_rsync_daemon_needed | Whether the `rsync-daemon` package is needed. If set to `true`, the `rsync-daemon` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_net_snmp_needed | Whether the `net-snmp` package is needed. If set to `true`, the `net-snmp` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_telnet_server_needed | Whether the `telnet-server` package is needed. If set to `true`, the `telnet-server` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_tftp_server_needed | Whether the `tftp-server` package is needed. If set to `true`, the `tftp-server` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_squid_needed | Whether the `squid` package is needed. If set to `true`, the `squid` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_httpd_needed | Whether the `httpd` package is needed. If set to `true`, the `httpd` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_nginx_needed | Whether the `nginx` package is needed. If set to `true`, the `nginx` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_xinetd_needed | Whether the `xinetd` package is needed. If set to `true`, the `xinetd` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_xorg_needed | Whether the `xorg` package is needed. If set to `true`, the `xorg` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_postfix_needed | Whether the `postfix` package is needed. If set to `true`, the `postfix` package will be remain installed and the services will be disabled instead. | bool | no |  | false |
| rhel8cis_ipv6_needed | Whether IPv6 is needed. | bool | no |  | false |
| rhel8cis_bluez_needed | Whether the `bluez` package is needed. If set to `true`, the `bluez` package will be remain installed and the services will be disabled instead. For workstations, this will default to `true`. | bool | no |  | false |
| rhel8cis_firewall | The firewall to use. | str | no | <ul><li>firewalld</li></ul> | firewalld |
| rhel8cis_sshd_allow_users | The users to allow for SSH. | list of 'str' | no |  |  |
| rhel8cis_sshd_allow_groups | The groups to allow for SSH. | list of 'str' | no |  | ["wheel"] |
| rhel8cis_sshd_deny_users | The users to deny for SSH. | list of 'str' | no |  |  |
| rhel8cis_sshd_deny_groups | The groups to deny for SSH. | list of 'str' | no |  |  |
| rhel8cis_sshd_removed_ciphers | The ciphers to remove from the SSH configuration. | list of 'str' | no |  | ["3des-cbc", "aes128-cbc", "aes192-cbc", "aes256-cbc", "rijndael-cbc@lysator.liu.se"] |
| rhel8cis_sshd_removed_kex_algorithms | The key exchange algorithms to remove from the SSH configuration. | list of 'str' | no |  | ["diffie-hellman-group1-sha1", "diffie-hellman-group14-sha1", "diffie-hellman-group-exchange-sha1"] |
| rhel8cis_sshd_removed_macs | The MACs to remove from the SSH configuration. | list of 'str' | no |  | ["hmac-md5", "hmac-md5-96", "hmac-ripemd160", "hmac-sha1-96", "umac-64@openssh.com", "hmac-md5-etm@openssh.com", "hmac-md5-96-etm@openssh.com", "hmac-ripemd160-etm@openssh.com", "hmac-sha1-96-etm@openssh.com", "umac-64-etm@openssh.com"] |
| rhel8cis_sshd_client_alive_interval | The interval for the client alive messages in seconds. | int | no |  | 15 |
| rhel8cis_sshd_client_alive_count_max | The maximum number of client alive messages. | int | no |  | 3 |
| rhel8cis_sshd_login_grace_time | The login grace time in seconds. | int | no |  | 60 |
| rhel8cis_sshd_max_auth_tries | The maximum number of authentication attempts. | int | no |  | 4 |
| rhel8cis_sshd_max_sessions | The maximum number of sessions. | int | no |  | 10 |
| rhel8cis_sshd_max_startups_before_dropping | The maximum number of startups before dropping. | int | no |  | 10 |
| rhel8cis_sshd_max_startups_drop_percentage | The maximum percentage of startups to drop. | int | no |  | 30 |
| rhel8cis_sshd_max_startups_absolute_maximum | The absolute maximum number of startups. | int | no |  | 60 |
| rhel8cis_sshd_log_level | The log level for SSH. | str | no | <ul><li>INFO</li><li>VERBOSE</li></ul> | INFO |
| rhel8cis_sudo_log_file | The log file for sudo. | path | no |  | /var/log/sudo.log |
| rhel8cis_sudo_authentication_timeout | The authentication timeout for sudo in seconds. | int | no |  | 15 |
| rhel8cis_su_group_name | The group name for the su command. | str | no |  | su |
| rhel8cis_su_group_members | The group members for the su command. | list of 'str' | no |  | ["root"] |
| rhel8cis_lockout_failed_attempts | The number of failed login attempts before lockout. | int | no |  | 5 |
| rhel8cis_lockout_unlock_time | The time in seconds to unlock the account. | int | no |  | 900 |
| rhel8cis_lockout_root_unlock_time | The time in seconds to unlock the root account. | int | no |  | 900 |
| rhel8cis_password_min_changed_characters | The minimum number of changed characters for a new password. | int | no |  | 2 |
| rhel8cis_password_min_length | The minimum length for a new password. | int | no |  | 14 |
| rhel8cis_password_max_repeat_characters | The maximum number of repeated characters for a new password. | int | no |  | 3 |
| rhel8cis_password_max_sequential_characters | The maximum number of sequential characters for a new password. | int | no |  | 3 |
| rhel8cis_passwords_remembered | The number of passwords remembered. | int | no |  | 24 |
| rhel8cis_password_expiration_days | The number of days before password expiration. | int | no |  | 365 |
| rhel8cis_password_expiration_warning_days | The number of days before password expiration warning. | int | no |  | 7 |
| rhel8cis_inactive_password_lock_days | The number of days before inactive password lock. | int | no |  | 30 |
| rhel8cis_syslog | The syslog configuration. | str | no | <ul><li>rsyslog</li><li>journald</li></ul> | rsyslog |
| rhel8cis_remote_log_server | The remote log server to use. | str | no |  | logserver.example.com |
| rhel8cis_journal_server_key_file | The journal server key file. | path | no |  | /etc/ssl/private/journal-upload.pem |
| rhel8cis_journal_server_cert_file | The journal server certificate file. | path | no |  | /etc/ssl/certs/journal-upload.pem |
| rhel8cis_journal_server_trusted_cert_file | The journal server trusted certificate file. | path | no |  | /etc/ssl/ca/trusted.pem |
| rhel8cis_journald_systemmaxuse | The maximum disk usage for the system journal. | str | no |  | 10M |
| rhel8cis_journald_systemkeepfree | The minimum disk space to keep free for the system journal. | str | no |  | 100G |
| rhel8cis_journald_runtimemaxuse | The maximum disk usage for the runtime journal. | str | no |  | 10M |
| rhel8cis_journald_runtimekeepfree | The minimum disk space to keep free for the runtime journal. | str | no |  | 100G |
| rhel8cis_journald_maxfilesec | The maximum file retention time. | str | no |  | 1month |
| rhel8cis_logrotate_frequency | The logrotate frequency. | str | no | <ul><li>daily</li><li>weekly</li><li>monthly</li></ul> | daily |
| rhel8cis_audit_backlog_limit | The audit backlog limit. | int | no |  | 8192 |
| rhel8cis_auditd_max_log_file | The maximum auditd log file size. | int | no |  | 10 |
| rhel8cis_auditd_disk_full_action | The action to take when the auditd disk is full. | str | no | <ul><li>single</li><li>halt</li></ul> | halt |
| rhel8cis_auditd_disk_error_action | The action to take when the auditd disk has an error. | str | no | <ul><li>single</li><li>halt</li><li>syslog</li></ul> | halt |
| rhel8cis_aide_cron_file | The file to use for the AIDE cron job. | path | no |  | /etc/cron.d/aide |
| rhel8cis_aide_cron_hour | The hour to run the AIDE cron job. | int | no |  | 5 |
| rhel8cis_aide_cron_minute | The minute to run the AIDE cron job. | int | no |  | 0 |

### Options for rhel8cis_chrony_servers
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| name | The NTP server name. | str | yes |  |  |
| options | The NTP server options. | list of 'str' | no |  |  |


## License
MIT

## Author and Project Information
Jim Tarpley
<!-- END_ANSIBLE_DOCS -->
