# gendloopBucket

A [Scoop](https://github.com/ScoopInstaller/Scoop) bucket. Summarize personal commonly used software.

Click here for [details](https://github.com/gendloop/gendloopBucket/wiki).

## Usage

1. Install scoop 
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
   ```

2. Add this bucket

   ```powershell
   scoop bucket add gendloopBucket https://github.com/gendloop/gendloopBucket
   ```

3. Install the software in the bucket
   ```powershell
   scoop install gendloopBucket/ClashForWindows
   ```

   

