# Lists
This section describes the following:

- [List - Unordered](#list-unordered)
- [List - Ordered](#list-ordered)
- [List - Nested](#list-nested)
- [Drop-down lists](#drop-down-lists)

---

## [List Unordered](#list-unordered)

Use only `-` for unordered lists. Using `+`, `*`, or a mix of these (or with `-`) does not render properly in all builds/browsers.

For sub nesting, please use `tab` key or 3 spaces for each additional level.


- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2

---
## [List Ordered](#list-ordered)

Use `1. ` for all list items. Markdown and output builders automatically take the next number of alphabet as the case maybe.

1. item 1
1. item 2
1. item 3
1. item 4


---
## [List Nested](#list-nested)

### Example


- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2

---

### Example


- item 1
- item 2
    1. sub-item 1
    2. sub-item 2
        - further nested item 1
        - further nested item 2

---

### Example 

1. item 1
1. item 2
    - sub-item 1
    - sub-item 2
        1. further nested item 1
        1. further nested item 2

---

1. list item:

   1. list item

   1. list item

1. list item

   1. list item
   1. list item
   1. list item:
      - list item
      - list item  
**Warning**  
Describe the warning

1. list item

---


## Drop-down lists

### Example

<details>
<summary>
Add title of your FAQ here
</summary>  

Add content of your FAQ here. You can add list/regular text.

</details>

---


### Example with ordered list

<details>
  <summary>a. Encrypt your hard disk to protect your data at rest</summary><br>

  1. Go to the **Apple** menu > **System Preferences** > **Security & Privacy**.
  2. Click the **FileVault** tab.
  3. If you see **Turn on FileVault**, go to step 4 or proceed to **Enable Full Disk Access(FDA)**.
  4. Click the lock icon and use your Touch ID or enter your password to unlock.
  5. Click **Turn on FileVault**.
  6. When prompted to specify how you would like to unlock your device if you forget your device password,  select **Create a recovery key and do not use my iCloud account**.

  <kbd>![create-recovery-key](images/onboarding-for-macos/create-recovery-key-1.png)</kbd>

   ?>  Save this key on a different device.

</details>

---

<details>
  <summary>b. Encrypt your hard disk to protect your data at rest</summary><br>

  1. Go to the **Apple** menu > **System Preferences** > **Security & Privacy**.
  2. Click the **FileVault** tab.
  3. If you see **Turn on FileVault**, go to step 4 or proceed to **Enable Full Disk Access(FDA)**.
  4. Click the lock icon and use your Touch ID or enter your password to unlock.
  5. Click **Turn on FileVault**.
  6. When prompted to specify how you would like to unlock your device if you forget your device password,  select **Create a recovery key and do not use my iCloud account**.

  <kbd>![create-recovery-key](images/onboarding-for-macos/create-recovery-key-1.png)</kbd>

   ?>  Save this key on a different device.

</details>

---

### Example with no lists

<details>
  <summary>Encrypt your hard disk to protect your data at rest</summary><br>

  - Go to the **Apple** menu > **System Preferences** > **Security & Privacy**.
  - Click the **FileVault** tab.
  - If you see **Turn on FileVault**, go to step 4 or proceed to **Enable Full Disk Access(FDA)**.
  - Click the lock icon and use your Touch ID or enter your password to unlock.
  - Click **Turn on FileVault**.
  - When prompted to specify how you would like to unlock your device if you forget your device password,  select **Create a recovery key and do not use my iCloud account**.

  <kbd>![create-recovery-key](images/onboarding-for-macos/create-recovery-key-1.png)</kbd>

   ?>  Save this key on a different device.

</details>