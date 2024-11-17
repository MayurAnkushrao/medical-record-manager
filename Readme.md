# Medical Record Management on Aptos Blockchain

## Introduction

The **Medical Record Management** module is a decentralized solution built on the Aptos blockchain, designed to enhance the security, transparency, and accessibility of medical records. This module allows patients to maintain ownership of their medical records and control access to authorized healthcare providers. By leveraging the blockchain's immutability and transparency, the system ensures data integrity and eliminates the need for a centralized authority.

## Vision of the Project

The vision of this project is to create a patient-centric healthcare ecosystem where individuals have complete control over their medical data. This module aims to:

1. **Empower Patients**: Grant ownership and control of medical records directly to patients.
2. **Enhance Privacy**: Ensure that medical data is only accessible by authorized entities.
3. **Improve Interoperability**: Facilitate secure sharing of medical data across healthcare providers.
4. **Leverage Blockchain Technology**: Utilize the benefits of blockchain for data immutability, transparency, and security.

## How It Works

1. **Medical Record Creation**: Patients can create a medical record by providing a hash of their data. This ensures the data itself remains private while the record is stored on the blockchain.
2. **Access Control**: Patients can grant access to specific healthcare providers by specifying their blockchain addresses. Only the authorized provider can access the medical record.

### Key Features

- **Patient Ownership**: The medical record is owned by the patient's blockchain account.
- **Access Management**: Patients can dynamically grant or revoke access to their records.
- **Data Security**: Medical data remains private, as only its hash is stored on the blockchain.

## Future Goals of the Project

The current implementation serves as a foundational layer for secure medical record management. Future goals include:

1. **Integration with Off-Chain Storage**: Link on-chain records to off-chain encrypted medical data repositories for complete record management.
2. **Role-Based Access Control**: Implement granular access control based on the role and permissions of healthcare providers.
3. **Audit Logging**: Provide an audit trail to track all access and modifications to medical records.
4. **Decentralized Identity Integration**: Enable identity verification using decentralized identity protocols for providers and patients.
5. **Cross-Network Compatibility**: Ensure compatibility with other blockchain networks for wider adoption.
6. **Smart Contract Upgradability**: Introduce mechanisms for seamless updates to the module without disrupting existing records.

## Deployed Address of the Project

The **Medical Record Management** module is deployed on the Aptos blockchain. Below is the deployed address:

**Deployed Address**: `0xc5acdae4e2cb14d15bdf01d30bb8963e4887f446d4f237c30edeacd2f3c76cf8`  


## Getting Started

1. **Prerequisites**: Ensure you have the Aptos CLI and an Aptos wallet set up.
2. **Deployment**: Deploy the module to your desired Aptos blockchain network.
3. **Usage**: Interact with the module by calling the following functions:
   - `create_record` to create a new medical record.
   - `grant_access` to grant access to a healthcare provider.

## Contributing

We welcome contributions from the community to enhance and expand the module's capabilities. If you're interested, please fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

--- 

For additional details or support, please reach out to the development team at **[mayurankushrao2004@gmail.com]**.