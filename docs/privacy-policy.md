# Privacy Policy

**Rental Host Expense Tracker**  
Last updated: April 14, 2026

## Overview

Rental Host Expense Tracker is a private iOS application designed for personal use by a single rental host to track business expenses, mileage, and generate tax reports.

## Data Collection

This app does not collect, share, or sell any personal data to third parties. There are no analytics SDKs, advertising networks, or third-party data collection services integrated into this app.

## Data Storage

All data entered into the app (expenses, receipts, mileage logs) is stored in a private AWS cloud account owned and controlled solely by the app owner. No data is accessible to any third party.

Receipt images are stored in a private Amazon S3 bucket. Expense and mileage records are stored in a private Amazon DynamoDB database. Both are protected by AWS security controls and are not publicly accessible.

## Authentication

The app uses secure authentication with bcrypt password hashing and JWT tokens. Login credentials are never stored in plain text. Authentication tokens are stored locally in the iOS Keychain.

## Camera and Photo Library Access

The app requests access to your camera and photo library solely to scan receipt images. These images are uploaded directly to your private AWS S3 bucket and are not shared with any third party.

## Receipt Processing

Receipt images are processed using Amazon Textract (OCR) and Anthropic Claude AI solely for the purpose of extracting expense information (store name, date, amount, line items). This processing occurs within your private AWS account and the results are stored only in your private database.

## No Third-Party Sharing

We do not share, sell, rent, or trade any information with third parties for their commercial purposes.

## Contact

If you have any questions about this privacy policy, please contact:

**Mittal Gadhia**  
Email: mittalgadhia@gmail.com
