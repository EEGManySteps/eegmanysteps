# DRAFT: Contributing to EEGManySteps

Welcome to **EEGManySteps**! We're excited that you're interested in contributing to this community-driven initiative focused on advancing mobile brain/body imaging (MoBI) research. This document provides comprehensive guidelines for different types of contributions to our project.

## Table of Contents

- [Getting Started](#getting-started)
- [Types of Contributions](#types-of-contributions)
- [Work Package Structure](#work-package-structure)
- [Technical Contributions](#technical-contributions)
- [Data Contributions](#data-contributions)
- [Communication and Collaboration](#communication-and-collaboration)
- [Recognition and Authorship](#recognition-and-authorship)
- [Development Workflow](#development-workflow)

## Getting Started

### Project Overview

EEGManySteps is an international collaborative effort that:
- Investigates how different experimental setups and analysis methods influence EEG results in mobile settings
- Emphasizes data collection across diverse settings rather than replicating specific findings
- Standardizes data acquisition and analysis protocols using BIDS format
- Fosters Open Science through publicly accessible research materials and datasets

### Before You Contribute

1. **Read our documentation**:
   - [Project description](./index.qmd)
   - [Team structure and roles](./team.qmd)
   - [Code of Conduct](./CODE_OF_CONDUCT.md)

2. **Join our communication channels**:
   - Discord server (primary communication)
   - GitHub repositories
   - OSF project: <https://osf.io/ec8wg/>

3. **Understand our values**:
   - Open Science principles
   - Collaborative and inclusive research practices
   - Reproducibility and transparency
   - Community-driven decision making

## Types of Contributions

### 1. Steering Committee (SC) Member

**Suggested Requirements**:
- Authorship in one or more peer-reviewed MoBI papers OR extensive experience in similar open science projects
- Availability for monthly meetings
- Minimum one-year active commitment

**Responsibilities**:
- Attend monthly SC meetings
- Lead or actively participate in assigned work packages
- Take on specific tasks and deliverables
- Communicate regularly with Advisory Board and other SC members
- Contribute to project decision-making and direction

**How to Apply**:
- Contact the EEG ManySteps Gmail Account (<eegmanysteps@gmail.com>) with:
  - Brief CV highlighting relevant experience
  - Statement of interest and availability
  - Preferred work package(s) for involvement

### 2. Advisory Board (AB) Member

**Suggested Requirements**:
- First or last author in peer-reviewed MoBI/Biomechanics papers OR extensive experience in similar open science projects
- Minimum one-year advisory commitment
- Established expertise in relevant research areas

**Responsibilities**:
- Attend quarterly/biannual AB meetings
- Provide guidance and feedback on project direction
- Review and advise on major decisions
- Support through mentorship and institutional connections
- Contribute expertise for protocol and analysis decisions

**How to Apply**:
- Invitation-based or contact SC members with:
  - Detailed CV highlighting relevant expertise
  - Letter of support for the project goals
  - Indication of specific areas where you can provide guidance

### 3. Data Contributors

**Suggested Requirements**:
- Responsible for acquisition, curation, or formatting of mobile EEG data
- Institutional ethics approval for data sharing
- Willingness to format data according to the requirements of the project and FAIR principles

**Types of Data Contributions**:
- **Existing Datasets**: Share previously collected mobile EEG data
- **New Data Collection**: Participate in standardized data collection using project protocols
- **Multi-modal Data**: Contribute EEG, motion, and potentially EMG data

**Data Requirements**:
- Mobile EEG recordings with gait or movement components
- Ethical approval for data sharing
- Complete metadata and experimental documentation
- Willingness to convert to the requirements of the project (BIDS format with additional requirements)

### 4. Analysts

**Suggested Requirements**:
- Experience with analysis of biomechanical or MoBI data
- Proficiency in Python and/or MATLAB
- Commitment to open science practices and code sharing

**Contribution Areas**:
- Develop and test preprocessing pipelines
- Conduct specific analyses related to research questions
- Validate and compare different analysis approaches
- Contribute to "gold standard" processing pipeline development
- Participate in multi-analyst validation studies

### 5. Community Contributors

**No formal requirements** - all levels of involvement welcome:
- Provide feedback on protocols and methods
- Participate in discussions and knowledge sharing
- Help with documentation and tutorials
- Assist with outreach and dissemination
- Contribute to code review and testing

## Work Package Structure

Our project is organized into work packages (WPs). You can contribute to one or multiple WPs based on your expertise and interests:

### WP1: Acquisition Protocols
**Focus**: Identify existing public datasets and coordinate data sharing
- Contact dataset authors for data sharing requests
- Develop surveys for data submission
- Catalog available datasets and their characteristics
- Coordinate with authors of unpublished datasets

**How to Contribute**:
- Help identify relevant datasets in the literature
- Assist with contacting dataset authors
- Support development of data submission surveys
- Contribute to dataset cataloging and metadata collection

### WP2: Data Collection
**Focus**: Design and implement standardized data collection protocols
- Develop final protocol and manual for data collection
- Provide technical support for experimental setups
- Design mobile paradigms (currently using Presentation software)
- Standardize hardware requirements (EEG systems, headphones, mobile devices)

**How to Contribute**:
- Provide feedback on experimental protocols
- Test protocols in your laboratory
- Contribute to hardware standardization discussions
- Help develop mobile paradigm implementations
- Share experience with mobile EEG setups

### WP3: Data Curation
**Focus**: Standardize and organize all project datasets
- Convert datasets to BIDS format for EEG and Motion data
- Identify and parameterize relevant covariates
- Develop templates for dataset properties
- Coordinate data upload to platforms (OpenNeuro, PublNEUro)

**How to Contribute**:
- Assist with BIDS conversion of datasets
- Help identify important covariates for analysis
- Contribute to metadata standardization
- Support data quality assessment and validation

### WP4: Analysis
**Focus**: Develop and implement analysis pipelines
- Create standardized preprocessing pipelines
- Develop feature extraction methods
- Implement multi-analyst validation approaches
- Compare analysis methods across datasets

**How to Contribute**:
- Develop preprocessing and analysis code
- Participate in pipeline validation studies
- Contribute to method comparison analyses
- Help establish "gold standard" processing approaches
- Share analysis expertise and best practices

### WP5: Dissemination
**Focus**: Share findings and create educational resources
- Organize paper writing and publication
- Create tutorials and documentation
- Plan workshops and conference presentations
- Manage project communication and outreach

**How to Contribute**:
- Assist with manuscript writing and review
- Create tutorials and educational materials
- Help organize workshops or conference sessions
- Support social media and outreach efforts
- Contribute to project documentation

### WP6: Funding
**Focus**: Secure resources for project sustainability
- Identify funding opportunities
- Write grant proposals
- Coordinate institutional support
- Manage resource allocation

**How to Contribute**:
- Identify relevant funding opportunities
- Contribute to grant proposal writing
- Provide institutional letters of support
- Share expertise in grant writing and funding strategies

### WP7: Research Questions
**Focus**: Coordinate research objectives and cross-WP collaboration
- Oversee development of research questions
- Coordinate between work packages
- Support potential collaborations
- Ensure alignment with project goals

**How to Contribute**:
- Propose research questions and hypotheses
- Help coordinate cross-WP activities
- Facilitate collaboration between different groups
- Contribute to strategic planning and oversight

## Technical Contributions

### Repositories and Platforms

We use several platforms for collaboration:

- **GitHub**: Code repositories, issue tracking, and version control
  - Main organization: <https://github.com/EEGManySteps>
  - Paradigms repository: <https://github.com/EEGManySteps/paradigms>
- **OSF**: Project coordination, documentation, and non-code materials
  - Project page: <https://osf.io/ec8wg/>
- **Discord**: Daily communication and coordination
- **Data platforms**: OpenNeuro, PublNEUro (for dataset sharing)

### Code Contributions

#### Programming Languages
- **Primary**: Python and MATLAB
- **Documentation**: Markdown, Quarto
- **Version Control**: Git/GitHub

#### Contribution Workflow
1. **Fork** the relevant repository
2. **Create** a feature branch for your contribution
3. **Develop** your code following our standards
4. **Test** your implementation thoroughly
5. **Document** your code and methods
6. **Submit** a pull request with clear description
7. **Respond** to review feedback and iterate

#### Code Standards
- Follow PEP 8 for Python code
- Use clear, descriptive variable and function names
- Include comprehensive docstrings and comments
- Provide example usage and test cases
- Ensure compatibility with common analysis environments

### Documentation Contributions

- **Tutorials**: Step-by-step guides for common tasks
- **API Documentation**: Comprehensive function and class documentation
- **Protocol Documentation**: Detailed experimental and analysis protocols
- **Best Practices**: Guidelines for data collection and analysis

## Data Contributions

### Data Submission Process

1. **Initial Contact**: Reach out to WP1 team about your dataset
2. **Ethics Verification**: Confirm approval for data sharing
3. **Data Assessment**: Work with WP3 to evaluate dataset compatibility
4. **BIDS Conversion**: Convert data to BIDS format (with support)
5. **Metadata Collection**: Provide comprehensive dataset documentation
6. **Upload Coordination**: Work with team to upload to appropriate platform

### Data Format Requirements

#### EEG Data
- **Format**: BIDS-EEG compliant
- **File types**: BrainVision (.vhdr, .vmrk, .eeg), EDF, or other standard formats
- **Sampling rate**: Documented and appropriate for analyses
- **Channel information**: Complete electrode positions and types
- **Event markers**: Clear experimental event coding

#### Motion Data
- **Format**: BIDS-Motion compliant
- **Sensors**: IMU, accelerometer, or motion capture data
- **Synchronization**: Clear temporal alignment with EEG data
- **Sampling rate**: Documented and sufficient for gait analysis

#### Metadata Requirements
- Participant demographics (age, sex, relevant characteristics)
- Experimental conditions and procedures
- Hardware specifications (EEG system, motion sensors)
- Environmental factors (indoor/outdoor, walking surface, etc.)
- Data collection parameters (sampling rates, filters, etc.)

### Data Sharing Ethics

- Obtain institutional ethics board approval for data sharing
- Ensure participant consent covers data sharing for research purposes
- Remove or pseudonymize all identifying information
- Follow GDPR and local privacy regulations
- Clearly document any data use restrictions

## Communication and Collaboration

### Meeting Structure

#### Steering Committee Meetings
- **Frequency**: Monthly
- **Format**: Virtual (with occasional in-person opportunities)
- **Duration**: 1-2 hours
- **Agenda**: Work package updates, decisions, planning
- **Scheduling**: Polls sent in advance to accommodate international team

#### Advisory Board Meetings
- **Frequency**: Quarterly or biannual
- **Format**: Virtual
- **Duration**: 1-2 hours
- **Purpose**: Strategic guidance, protocol review, major decisions

#### Work Package Meetings
- **Frequency**: As needed by each WP
- **Format**: Virtual, smaller groups
- **Purpose**: Specific task coordination and progress updates

### Communication Channels

#### Discord (Primary)
- Daily coordination and quick questions
- Work package specific channels
- General project discussion
- File sharing and updates

#### Email
- Formal communications and decisions
- External collaborator outreach
- Important announcements

#### GitHub
- Code-related discussions
- Issue tracking and feature requests
- Technical documentation

### Collaboration Guidelines

- **Responsiveness**: Aim to respond to communications within 48 hours
- **Transparency**: Share progress, challenges, and changes openly
- **Inclusion**: Ensure all relevant stakeholders are included in decisions
- **Documentation**: Record important decisions and rationale
- **Time zones**: Be mindful of international collaboration challenges

## Recognition and Authorship

### Authorship Guidelines

We follow established academic standards for authorship while recognizing diverse contributions:

#### Lead Authorship
- Substantial contribution to conception, design, analysis, or interpretation
- Drafting or critically revising intellectual content
- Final approval of version to be published
- Agreement to be accountable for all aspects of work

#### Co-authorship
- Significant contribution to one or more work packages
- Meaningful participation in data collection, analysis, or interpretation
- Contribution to manuscript preparation or review
- Meeting minimum time commitment requirements

#### Acknowledgment
- Technical support and assistance
- Resource provision (funding, equipment, facilities)
- Brief consultations and feedback
- Administrative support

### Contribution Recognition

Beyond traditional authorship, we recognize contributions through:
- **Website Recognition**: Listed contributors on project website
- **Conference Presentations**: Co-presenter opportunities
- **Software Attribution**: Credit in code repositories and documentation
- **Dataset Attribution**: Recognition in data publications and repositories

### Publication Strategy

- **Primary Publications**: Major findings and method comparisons
- **Methods Papers**: Protocol descriptions and validation studies
- **Data Papers**: Dataset descriptions and sharing announcements
- **Tutorial Papers**: Educational and methodological guidance

## Development Workflow

### Issue Tracking

Use GitHub Issues for:
- **Bug Reports**: Clear description, reproduction steps, expected vs. actual behavior
- **Feature Requests**: Detailed description of proposed functionality
- **Documentation**: Improvements and additions needed
- **Questions**: Technical or procedural clarifications

### Pull Request Process

1. **Create Issue**: Describe the problem or enhancement
2. **Fork Repository**: Create your own copy for development
3. **Create Branch**: Use descriptive branch names (e.g., `fix-preprocessing-bug`)
4. **Develop**: Make your changes with appropriate tests
5. **Document**: Update relevant documentation
6. **Test**: Ensure all tests pass and functionality works
7. **Submit PR**: Reference related issues and provide clear description
8. **Review**: Respond to feedback and make requested changes
9. **Merge**: Maintainer will merge after approval

### Testing and Quality Assurance

- **Code Testing**: Include unit tests for new functions
- **Integration Testing**: Ensure compatibility with existing codebase
- **Documentation Testing**: Verify examples and tutorials work
- **Peer Review**: All significant contributions reviewed by team members

### Release Process

- **Versioning**: Follow semantic versioning for software releases
- **Documentation**: Update changelog and release notes
- **Testing**: Comprehensive testing before releases
- **Communication**: Announce releases through appropriate channels

## Getting Help

### Technical Support
- GitHub Issues for code-related problems
- Discord channels for quick questions
- Work package leads for specific domain questions

### Project Information
- **EEG ManySteps Gmail Account**: <eegmanysteps@gmail.com> (Website responsibility, general inquiries)
- **Steering Committee**: Available through Discord or email
- **Work Package Leads**: Contact appropriate WP lead for specific areas

### Resources
- [Project Documentation](./index.qmd)
- [Team Information](./team.qmd)
- [OSF Project](https://osf.io/ec8wg/)
- [GitHub Organization](https://github.com/EEGManySteps)

## Conclusion

EEGManySteps thrives because of community contributions from researchers around the world. Whether you're contributing data, code, expertise, or simply participating in discussions, your involvement helps advance our understanding of mobile brain/body imaging and supports Open Science principles.

We're committed to making participation accessible, inclusive, and rewarding for all contributors. If you have questions, suggestions, or need support getting started, please don't hesitate to reach out through any of our communication channels.

Thank you for your interest in contributing to EEGManySteps!

---

**Last Updated**: 23/05/2025  
**Version**: 0.1
