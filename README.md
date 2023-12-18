# sam-vpc
```mermaid
flowchart TB;
    subgraph &nbsp;
        rootPublicSubnetA[PublicSubnetA<br/>EC2::Subnet]-->rootVPC[VPC<br/>EC2::VPC]
        rootPublicSubnetC[PublicSubnetC<br/>EC2::Subnet]-->rootVPC[VPC<br/>EC2::VPC]
        rootPrivateSubnetA[PrivateSubnetA<br/>EC2::Subnet]-->rootVPC[VPC<br/>EC2::VPC]
        rootPrivateSubnetC[PrivateSubnetC<br/>EC2::Subnet]-->rootVPC[VPC<br/>EC2::VPC]
end

```

# Create
```
sam init
```

# Delete
```
sam delete
```
