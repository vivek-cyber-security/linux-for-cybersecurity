## Mini Lab 1 – File Permission Hardening

## Objective
- Understand Linux file permissions
- Secure sensitive files using chmod
- Apply principle of least privilege

## Step 1: Create Sensitive File

- Command used:
  touch 1.txt
  echo "This is confidential data" > secret.txt

- Checked permission:
  ls -l 1.txt

## Screenshot – Before Permission Change

## Step 2: Secure the File

- Command used:
  chmod 600 1.txt

- Verified permission:
  ls -l 1.txt

## Screenshot – After Permission Change

## Security Learning

- 600 permission allows only owner access
- Prevents unauthorized reading
- Follows least privilege principle
- Important for protecting confidential files

## Conclusion

- Successfully hardened file permissions
- Understood real Linux security control
- Practiced practical cybersecurity concept

## End of Mini Lab 1
