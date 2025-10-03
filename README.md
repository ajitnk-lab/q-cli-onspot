# Q CLI Spot Instance Setup

This repository contains a complete setup for AWS Q CLI development environment using EC2 Spot instances, including website files, CloudFormation templates, and deployment scripts.

## Repository Contents

### 🌐 Website Projects
- **FINAL-COMPLETE-WEBSITE-WITH-FIXES/**: Latest version with bug fixes and enhancements
- **FINAL-COMPLETE-WEBSITE/**: Previous stable version
- **cloudnestle-website-COMPLETED/**: Completed CloudNestle website implementation

### ☁️ Infrastructure & Deployment
- **cloudformation/**: CloudFormation templates for AWS infrastructure
- **deployment-scripts/**: Automated deployment scripts
- **enhanced-scripts/**: Enhanced user data scripts with Gemini integration
- **qclivscode-cfn_template.yaml**: Main CloudFormation template for Q CLI VSCode setup

### 🔧 Configuration
- **config/**: Configuration files for Gemini and other services
- **mcp*.json**: MCP (Model Context Protocol) server configurations
- **test-scripts/**: Testing utilities

### 📚 Documentation
- **documentation/**: Setup guides and documentation
- **website_generation_prompt*.md**: Comprehensive prompts for website generation
- **sagemaker-vscode-setup.md**: SageMaker VSCode setup guide
- **flask-todo-cdk-development.md**: Flask TODO app development guide

### 🔑 Security & Keys
- **amazon-q-key-uswest2.pem**: AWS key pair for US West 2
- **privatekey.ppk**: Private key in PuTTY format

## Quick Start

### 1. Deploy Infrastructure
```bash
# Deploy using CloudFormation
./quick-deploy-qcli-vscode.sh

# Or use the comprehensive deployment script
./cfn-deployment-script.sh
```

### 2. Setup Development Environment
```bash
# Start Q CLI environment
./qstart.sh

# Download and deploy complete setup
./download-and-deploy.sh
```

### 3. Enhanced Setup with Gemini
```bash
# Deploy with Gemini integration
./deployment-scripts/deploy-gemini-enhanced-script.sh

# Install Gemini on current instance
./deployment-scripts/install-gemini-current-instance.sh
```

## Features

### 🚀 Complete Development Environment
- Pre-configured VSCode with AWS extensions
- Q CLI with MCP server integration
- Automated EC2 Spot instance management
- Cost-optimized infrastructure

### 🤖 AI Integration
- Gemini AI integration for enhanced development
- GitHub Copilot support
- MCP servers for extended functionality

### 🌐 Full-Stack Website
- Modern responsive design
- Authentication system
- AWS services integration
- Industry-specific solutions

### 📊 Monitoring & Analytics
- Performance tracking
- Cost optimization tools
- Security compliance monitoring

## Architecture

The setup creates:
- EC2 Spot instances for cost efficiency
- Auto Scaling Groups for reliability
- Load Balancers for high availability
- S3 buckets for storage
- CloudWatch for monitoring

## Configuration Files

### MCP Servers
- `mcp.json`: Main MCP configuration
- `mcp-16-july-withgithub.json`: GitHub integration
- `mcp_backup_2025-07-25_17-55-36_IST.json`: Backup configuration

### Gemini Integration
- `config/gemini-config.json`: Gemini API configuration
- `config/gemini-config.toml`: TOML format configuration

## Website Features

The included websites provide:
- **AI-Powered Solutions**: Machine learning and AI service recommendations
- **Industry Solutions**: Tailored solutions for different industries
- **Assessment Tools**: Well-Architected Framework assessments
- **Cost Optimization**: Tools and recommendations for cost management
- **Security Frameworks**: Security maturity assessments
- **Training Resources**: Learning paths and certification tracking

## Security Notes

⚠️ **Important**: This repository contains private keys and sensitive configuration files. Ensure proper access controls and rotate keys regularly.

## Support

For issues and questions:
1. Check the documentation in the `documentation/` folder
2. Review the setup guides and prompts
3. Use the test scripts to validate your setup

## License

This project is for educational and development purposes. Please review AWS terms of service and ensure compliance with your organization's policies.

---

**Last Updated**: July 2025  
**Version**: 1.0  
**Compatibility**: AWS Q CLI, VSCode, EC2 Spot Instances