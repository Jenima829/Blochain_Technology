🔗 Blockchain-based Academic Certificate Verification

 📌 Project Overview
        -> This project is a simplified blockchain application that ensures the authenticity of student academic certificates. Instead of traditional paper-based certificates, each certificate is stored as a block in a blockchain. This makes it tamper-proof — if anyone tries to modify data, the chain breaks, and the fraud is detected.

  The system includes:
 👩‍🏫 Multi-user authentication (for incharges/teachers).
 🔑 Password protection & forgot-password recovery using a common secret code.
 📚 Section, Year of Study, and Subject-based entry of student certificate details.
🎓 Certificate ID auto-generation (e.g., English → E001, E002, …).
 🔍 Certificate Verification by entering the Certificate ID.
------------------------------------------
##⚡ Features:
### 1.Secure Authentication
-Only authorized incharges can log in with username and password.
-If the password is entered wrong twice, the system flags suspicious activity and notifies the admin.
-Forgot password? → Enter the common secret code to reset access.

###2.Certificate Entry : Incharge selects Year, Section, Subject once → all student entries belong to that context.
###Each certificate stores: Student Name,Roll Number,Subject,Year & Section,Percentage Score
###-A unique Certificate ID is generated (Subject initial + unique number).

###3.Blockchain Security : Hash of the block and Previous block hash
###4.Verification System : HRs, Universities, or anyone can enter a Certificate ID and instantly check if it exists in the blockchain.
------------------------------------------

##🏗️ Tech Stack
###Language: Python 3
###Core Concepts: Blockchain (Hashing, Blocks, Chain Verification)
###Security: Username-password authentication + secret code recovery.
