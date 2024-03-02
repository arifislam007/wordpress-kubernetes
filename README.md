# wordpress-kubernetes
This is a demo application deployment of Wordpress 
WordPress is a free and open-source content management system (CMS) that allows users to create, manage, and publish websites and blogs. WordPress offers a user-friendly interface, extensive customization options through themes and plugins, and robust community support. </br>

# Execute file as per secquence
1. namespace.yaml
2. PersistentVolume.yaml
3. persistentVolumeClaim.yaml
4. secret.yaml (Befor executing secret.yaml run this on cli on kubernet master:  echo "Mypass123" | base64 )
5. mysql.yaml
6. mysql-service.yaml
7. wordpress-deployment.yaml
8. wordpress-service.yaml
