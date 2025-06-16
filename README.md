# Fully-Private-EKS-Cluster
Creation of fully private aws eks cluster with related services (ebs, secretnmanager, and more ... )

1. Create VPC for eks cluster
   it contains from two az's. Each az has 2 private subnets and 1 public subnet
   ![image](https://github.com/user-attachments/assets/3d9964a7-37af-434e-ab53-4358b97b37cf)
   ![image](https://github.com/user-attachments/assets/66e2bb31-fc4c-4b13-86ab-875786a1535d)

   VPC Preview:
   ![image](https://github.com/user-attachments/assets/f192ccf4-7588-46eb-b40f-be35c7f15f1d)

2. Create bastion Host to access the kube-api server and the cluster

   ![image](https://github.com/user-attachments/assets/ccae921a-970f-4fcd-94f2-f074b2e851b8)
   ![image](https://github.com/user-attachments/assets/3e1a52c5-e892-4e72-a75b-ce475f5eb5cc)
   ![image](https://github.com/user-attachments/assets/7701fa6a-acbb-4453-bd77-692fb937bbab)
   ![image](https://github.com/user-attachments/assets/b4ffe105-c068-4592-b162-5e980f1d777a)
   ![image](https://github.com/user-attachments/assets/19b94604-6e7a-45f5-b6c7-a14e33f4b4d6)

3. Create EKS cluster:

   ![image](https://github.com/user-attachments/assets/dbe1d8da-c7d5-4810-9cb9-5ff942107c9b)
   create role for the eks control plane
   ![image](https://github.com/user-attachments/assets/88da32ab-ee20-45b6-ba4a-0b4090e1d4e4)
   ![image](https://github.com/user-attachments/assets/0b19c629-e3a6-4e3f-8136-77d64247443a)
   ![image](https://github.com/user-attachments/assets/c12db90c-2f99-4b63-9582-04bf2363ae3f)
   ![image](https://github.com/user-attachments/assets/03345dc1-edef-4b98-9a1b-0f50062a644d)
   
   ![image](https://github.com/user-attachments/assets/f8e64b4c-4a97-4a25-a4ae-7fc11eaaefe9)
   ![image](https://github.com/user-attachments/assets/685cb4d1-bb30-43b1-8ac9-88be55508b31)
   ![image](https://github.com/user-attachments/assets/aa850396-737e-4dae-b749-4121b8550cb6)
   ![image](https://github.com/user-attachments/assets/0b440084-59b5-4947-899b-6436c8fb7e85)
   ![image](https://github.com/user-attachments/assets/2d0328be-84e3-4737-924c-6929009d6c45)
   ![image](https://github.com/user-attachments/assets/8537e5ca-154f-4afc-a353-165d43ee6fad)
   ![image](https://github.com/user-attachments/assets/4531c684-7ebd-44d7-ad46-705f44405a6d)
   ![image](https://github.com/user-attachments/assets/01e9a388-75ef-4ecb-994d-f9b63cbaacde)
   ![image](https://github.com/user-attachments/assets/d2fdc8cf-7502-42be-bc03-f8c356cf54e2)
   ![image](https://github.com/user-attachments/assets/ced677a5-2a44-4342-a17c-111cf2745733)
   ![image](https://github.com/user-attachments/assets/fe478a85-bf8c-4b20-a5ec-e7c3190122a9)
   ![image](https://github.com/user-attachments/assets/e0eebd72-00e0-416c-a1b8-d8b31449b2ee)
   # note: I also added cert manager (community) add-on

4. Create Node Group for the cluster:
   ![image](https://github.com/user-attachments/assets/a49c3596-ebc7-419e-ad33-4b034592edc8)
   ![image](https://github.com/user-attachments/assets/bc68e2e3-6cdd-4123-bc4f-ebe5fa5f7563)
   ![image](https://github.com/user-attachments/assets/0ee3394b-6679-4f80-8056-06567c46945d)
   ![image](https://github.com/user-attachments/assets/f9f389db-d932-4a07-b933-cfbb248bbdc5)
   ![image](https://github.com/user-attachments/assets/d042c84f-2c62-49da-9559-b3cea89a861a)
   ![image](https://github.com/user-attachments/assets/f7e00b6a-4941-4e40-8f12-596e9d9738cd)
   ![image](https://github.com/user-attachments/assets/df4c60e7-57cf-4b56-a7bb-4379152a8a04)
   ![image](https://github.com/user-attachments/assets/b9f15612-b1b7-49c7-8f99-518edd89c3b7)
   ![image](https://github.com/user-attachments/assets/ddc2799d-c4eb-44ec-945c-7328de118e8d)
   ![image](https://github.com/user-attachments/assets/c7666a90-6172-4150-b062-126475005fcc)
   ![image](https://github.com/user-attachments/assets/f7d0eafe-0644-4197-8034-48bf7bbf3f24)
   ![image](https://github.com/user-attachments/assets/2941815f-ee37-43dd-a795-05429e67623d)
   ![image](https://github.com/user-attachments/assets/80ab33eb-99ba-4c2b-8037-afebd82b2c1b)




   

   





