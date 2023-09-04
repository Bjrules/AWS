Documentaion of Manual Implementation of 2 Company website using reverse proxy Technology
Project15 of Darey.io 
By Banjo BABADE
Configuration files for this project can be found at : https://github.com/Bjrules/BB-project-config.git

Watch full Video here: https://www.youtube.com/watch?v=XhmIBMzss5M&list=PLtPuNR8I4TvmKE9LJI11vALrnrXt8wLXD&index=6&t=7901s 

1. created my VPC BB-VPC-PRJ15

![Alt text](IMG/Screenshot_20230720_130757.png)
![Alt text](IMG/Screenshot_20230720_131457.png)
2. attched my vpc to Internet gateway
![Alt text](IMG/Screenshot_20230720_132943.png)

3. Create public Subnets
![Alt text](IMG/Screenshot_20230720_134520.png)
![Alt text](IMG/Screenshot_20230720_134800.png)
![Alt text](IMG/Screenshot_20230720_135512.png)
 
 created private subnets ass well
4. create route table.
![Alt text](IMG/Screenshot_20230720_143035.png)

5. associate the public and private subnets with their respective route tables
![Alt text](IMG/Screenshot_20230720_143245.png)
![Alt text](IMG/Screenshot_20230720_143252.png)
![Alt text](IMG/Screenshot_20230720_143342.png)
![Alt text](IMG/Screenshot_20230720_143442.png)
![Alt text](IMG/Screenshot_20230720_144019.png)
![Alt text](IMG/Screenshot_20230720_144112.png)
![Alt text](IMG/Screenshot_20230720_144350.png)

6. Create and allocate elasticIP
![Alt text](IMG/Screenshot_20230720_144354.png)
![Alt text](IMG/Screenshot_20230720_144820.png)
![Alt text](IMG/Screenshot_20230720_145357.png)
![Alt text](IMG/Screenshot_20230720_145656.png)

7. Creating NAT gateway for Private Subnets to be able top access the Internet
![Alt text](IMG/Screenshot_20230720_145706.png)
![Alt text](IMG/Screenshot_20230720_150313.png)
![Alt text](IMG/Screenshot_20230720_151202.png)
![Alt text](IMG/Screenshot_20230720_151244.png)

8. Editing routes of the private route table for private subnets
![Alt text](IMG/Screenshot_20230720_151244.png)
![Alt text](IMG/Screenshot_20230720_151312.png)
![Alt text](IMG/Screenshot_20230720_151356.png)

9. Create security Groups.
![Alt text](IMG/Screenshot_20230720_151557.png)
![Alt text](IMG/Screenshot_20230720_151602.png)
![Alt text](IMG/Screenshot_20230720_154035.png)

![Alt text](IMG/Screenshot_20230720_154639.png) 
![Alt text](IMG/Screenshot_20230720_154646.png) 
![Alt text](IMG/Screenshot_20230720_154803.png) 
![Alt text](IMG/Screenshot_20230720_155225.png) 
![Alt text](IMG/Screenshot_20230720_155325.png) 
![Alt text](IMG/Screenshot_20230720_155556.png) 
![Alt text](IMG/Screenshot_20230720_155916.png)
 ![Alt text](IMG/Screenshot_20230720_160050.png) 
 ![Alt text](IMG/Screenshot_20230720_160227.png) 
 ![Alt text](IMG/Screenshot_20230720_160401.png) 
 ![Alt text](IMG/Screenshot_20230720_160853.png) 
 ![Alt text](IMG/Screenshot_20230720_160901.png) 
 ![Alt text](IMG/Screenshot_20230720_161903.png) 
 ![Alt text](IMG/Screenshot_20230720_162149.png) 
 ![Alt text](IMG/Screenshot_20230720_162542.png) 
 ![Alt text](IMG/Screenshot_20230720_162554.png) 
 ![Alt text](IMG/Screenshot_20230720_162633.png)
  ![Alt text](IMG/Screenshot_20230720_162815.png)
   ![Alt text](IMG/Screenshot_20230720_163328.png)
    ![Alt text](IMG/Screenshot_20230720_163631.png) 
    ![Alt text](IMG/Screenshot_20230720_163705.png) 
    ![Alt text](IMG/Screenshot_20230720_163803.png) 
    ![Alt text](IMG/Screenshot_20230720_163844.png) 
    ![Alt text](IMG/Screenshot_20230720_164231.png) 
    ![Alt text](IMG/Screenshot_20230720_164241.png)

10. Created Hosted zone under Route53 so as to import my domain
![Alt text](IMG/Screenshot_20230724_114911.png)
![Alt text](IMG/Screenshot_20230724_115421.png)

11. Requst a certificate from AWS Certificate Manager ACM and create DNS records
![Alt text](IMG/Screenshot_20230724_114911.png)
![Alt text](IMG/Screenshot_20230724_122137.png)
![Alt text](IMG/Screenshot_20230724_122546.png)
![Alt text](IMG/Screenshot_20230724_122624.png)

12. Creating of File System EFS and accesspoints for wordpress and tooling
![Alt text](IMG/Screenshot_20230724_123410.png)
![Alt text](IMG/Screenshot_20230724_125324.png)
![Alt text](IMG/Screenshot_20230724_125416.png)
![Alt text](IMG/Screenshot_20230724_131308.png)
![Alt text](IMG/Screenshot_20230724_131615.png)
![Alt text](IMG/Screenshot_20230724_131929.png)
![Alt text](IMG/Screenshot_20230724_131934.png)
![Alt text](IMG/Screenshot_20230724_131940.png)
![Alt text](IMG/Screenshot_20230724_132124.png)
![Alt text](IMG/Screenshot_20230724_132158.png)

13. create KMS for my RDS
![Alt text](IMG/Screenshot_20230724_133208.png)
![Alt text](IMG/Screenshot_20230724_133718.png)
![Alt text](IMG/Screenshot_20230724_133728.png)


14. Create RDS and RDS subnet Group.
![Alt text](IMG/Screenshot_20230724_155343.png)
![Alt text](IMG/Screenshot_20230724_155815.png)
![Alt text](IMG/Screenshot_20230724_155822.png)
![Alt text](IMG/Screenshot_20230724_155837.png)
![Alt text](IMG/Screenshot_20230724_155957.png)
![Alt text](IMG/Screenshot_20230724_160006.png)

15. Installations and Configurations on Bastion Server (kindly refer to: https://github.com/Bjrules/BB-project-config/blob/main/Installation.md )
![Alt text](IMG/Screenshot_20230724_162156.png) 
![Alt text](IMG/Screenshot_20230724_174410.png) 
![Alt text](IMG/Screenshot_20230724_175036.png) 
![Alt text](IMG/Screenshot_20230724_175652.png) 
![Alt text](IMG/Screenshot_20230724_183330.png) 
![Alt text](IMG/Screenshot_20230724_183703.png) 
![Alt text](IMG/Screenshot_20230724_184105.png) 
![Alt text](IMG/Screenshot_20230724_184335.png) 
![Alt text](IMG/Screenshot_20230724_184532.png) 
![Alt text](IMG/Screenshot_20230724_184655.png) 
![Alt text](IMG/Screenshot_20230724_184755.png) 
![Alt text](IMG/Screenshot_20230724_194424.png) 
![Alt text](IMG/Screenshot_20230724_194444.png)

16. Creating AMIs for webservers, Bastion and Nginx
![Alt text](IMG/Screenshot_20230724_194746.png)
![Alt text](IMG/Screenshot_20230724_194942.png)
![Alt text](IMG/Screenshot_20230725_110549.png)

17. Create Target Groups
![Alt text](IMG/Screenshot_20230725_112134.png)

18. Creating Internal and External Load Balancers, Setting Headers.
![Alt text](IMG/Screenshot_20230725_135038.png)
![Alt text](IMG/Screenshot_20230725_140016.png)
![Alt text](IMG/Screenshot_20230725_140023.png) 
![Alt text](IMG/Screenshot_20230725_140042.png) 
![Alt text](IMG/Screenshot_20230725_140151.png) 
![Alt text](IMG/Screenshot_20230725_142809.png) 
![Alt text](IMG/Screenshot_20230725_170103.png) 
![Alt text](IMG/Screenshot_20230725_171023.png) 
![Alt text](IMG/Screenshot_20230725_171033.png) 
![Alt text](IMG/Screenshot_20230725_171041.png) 
![Alt text](IMG/Screenshot_20230725_171051.png) 
![Alt text](IMG/Screenshot_20230725_171100.png) 
![Alt text](IMG/Screenshot_20230725_171129.png) 
![Alt text](IMG/Screenshot_20230725_172022.png) 
![Alt text](IMG/Screenshot_20230725_172104.png) 
![Alt text](IMG/Screenshot_20230725_172145.png) 
![Alt text](IMG/Screenshot_20230725_172158.png) 
![Alt text](IMG/Screenshot_20230725_173306.png) 
![Alt text](IMG/Screenshot_20230725_173347.png) 
![Alt text](IMG/Screenshot_20230725_173630.png)

19. Creating Launch Templates kindly refrence configuration files https://github.com/Bjrules/BB-project-config.
![Alt text](IMG/Screenshot_20230725_190937.png)
![Alt text](IMG/Screenshot_20230725_191216.png)
![Alt text](IMG/Screenshot_20230725_191223.png)
![Alt text](IMG/Screenshot_20230725_192124.png)
![Alt text](IMG/Screenshot_20230725_190937.png) 
![Alt text](IMG/Screenshot_20230725_191216.png) 
![Alt text](IMG/Screenshot_20230725_191223.png) 
![Alt text](IMG/Screenshot_20230725_192124.png) 
![Alt text](IMG/Screenshot_20230725_192139.png) 
![Alt text](IMG/Screenshot_20230725_192400.png) 
![Alt text](IMG/Screenshot_20230725_195243.png)
 ![Alt text](IMG/Screenshot_20230725_195346.png)
  ![Alt text](IMG/Screenshot_20230725_195406.png) 
  ![Alt text](IMG/Screenshot_20230725_195951.png) 
  ![Alt text](IMG/Screenshot_20230725_205345.png) 
  ![Alt text](IMG/Screenshot_20230725_205354.png) 
  ![Alt text](IMG/Screenshot_20230725_205400.png) 
  ![Alt text](IMG/Screenshot_20230725_205407.png) 
  ![Alt text](IMG/Screenshot_20230725_205415.png) 
  ![Alt text](IMG/Screenshot_20230725_205658.png) 
  ![Alt text](IMG/Screenshot_20230725_205712.png) 
  ![Alt text](IMG/Screenshot_20230725_205906.png) 
  ![Alt text](IMG/Screenshot_20230725_210543.png) 
  ![Alt text](IMG/Screenshot_20230725_210802.png) 
  ![Alt text](IMG/Screenshot_20230725_211026.png) 
  ![Alt text](IMG/Screenshot_20230725_211507.png) 
  ![Alt text](IMG/Screenshot_20230725_214003.png) 
  ![Alt text](IMG/Screenshot_20230725_214013.png) 
  ![Alt text](IMG/Screenshot_20230725_214730.png) 
  ![Alt text](IMG/Screenshot_20230725_215437.png) 
  ![Alt text](IMG/Screenshot_20230725_230643.png) 
  ![Alt text](IMG/Screenshot_20230726_001633.png) 
  ![Alt text](IMG/Screenshot_20230726_001819.png)
   ![Alt text](IMG/Screenshot_20230726_005616.png) 
   ![Alt text](IMG/Screenshot_20230726_005623.png) 
   ![Alt text](IMG/Screenshot_20230726_005727.png) 
   ![Alt text](IMG/Screenshot_20230726_005759.png) 
   ![Alt text](IMG/Screenshot_20230726_010538.png) 
   ![Alt text](IMG/Screenshot_20230726_010851.png) 
   ![Alt text](IMG/Screenshot_20230726_010944.png)