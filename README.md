# AgroShield Store
Full-stack agriculture e-commerce starter: React/Vite + Express + PostgreSQL/RDS.

Local: create PostgreSQL database `agroshield`; backend `npm install`, copy `.env.example .env`, `npm run migrate`, `npm run seed`, `npm start`; frontend `npm install`, copy `.env.example .env`, `npm run dev`.
Demo: farmer@agroshield.demo / Farmer@123

Production: S3/CloudFront for React, Elastic Beanstalk for Node API, private Amazon RDS PostgreSQL. Use Secrets Manager/Parameter Store, HTTPS, private subnets, backups, monitoring, object storage for images and an approved payment gateway before real sales.

Demo crop-protection text is not agricultural advice. Real products must comply with Indian registration, label, dosage, crop, safety and sale requirements.
