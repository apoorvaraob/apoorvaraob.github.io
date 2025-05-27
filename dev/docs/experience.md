---
title: Experience
resume:
    timeline:
      - timePeriod: "June 2025 - Present"
        location: "Seattle, WA"
        logo: <img src="../images/aws.png" alt="AWS logo" height="40px" class="company-logo">
        title: "Software Development Engineer<br>AWS Security Assurance"
        descriptions:
        - Lead development of security assessment and compliance automation tools that help AWS services exceed the security and compliance expectations of regulators, auditors, and customers globally.
        - Design and implement scalable solutions that stand up to the scrutiny of external regulators and inspection by AWS's most security-sensitive customers.
        - Collaborate with a multidisciplinary team of software engineers, security engineers, technical product/program managers, data engineers, and compliance specialists to build customer trust through innovative security solutions.
      - timePeriod: "August 2022 - January 2025"
        location: "Bellevue, WA"
        logo: <img src="../images/amazon.png" alt="Amazon logo" height="40px" class="company-logo">
        title: "Software Development Engineer and Research Engineer<br>Applied AI - Amazon Worldwide Stores"
        descriptions:
        - Identified customer pain points, explored relevant recent research addressing similar challenges, developed proof of concept or minimally viable/lovable product, iterated on prototype, and conducted user acceptance tests for Human-in-the-loop tools like Computer Vision Annotation Tool (CVAT) and AWS Sagemaker Groundtruth for Prime Air data annotations.
        - Developed a geocode verification prototype using AWS Bedrock Agents that mirrors auditor workflows by integrating external APIs (Bing, ESRI, HereMaps) for Last Mile Analytics. The initial phase achieved promising accuracy and recall on curated groundtruth data, helping shape the future project roadmap.
        - Led comprehensive security and privacy reviews for handling classified customer data to meet industry compliance standards Earned the "Mission Impossible" award for rapidly building customer trust through security implementations with agile. Managed service-level security certifications for a 40+ person organization and shared best practices across teams. Additionally, implemented security measures for a worldwide fulfillment center stowing and shelf recognition automation project, contributing to an $8.8MM YoY reduction in cost to serve.
        - Co-led product development for SmartSifting, a model training accelerator library achieving up to 35% efficiency gains, through creating whitepapers, presentations, press releases, and FAQs. Incorporated private beta feedback from major AWS customers to improve user experience before launching in the AWS Sagemaker Deep Learning Container.
        - Cut experimentation setup time by 50% for science teams working on AI agents by implementing an experiment harness on AWS Sagemaker Studio and providing targeted documentation.
      - timePeriod: "2023 - 2026 (Expected)"
        location: "Seattle, WA"
        logo: <img src="../images/uw.png" alt="UW logo" height="125px" class="education-logo">
        title: "MBA, Technology Management<br>University of Washington Foster School of Business"
        descriptions:
          - "Coursework in Strategic Management of Technology & Innovation, focusing on dynamics of tech-driven industries and frameworks for managing technology-intensive businesses"
          - "Advanced studies in Entrepreneurship and Customer Experience Strategy, including venture creation, startup financing, and CX methodology"
          - "Specialized training in Tools for analytics-driven business insights"
          - "Leadership development through courses in Ethical Leadership, Leading Organizational Change, and Building Effective Teams"
      - timePeriod: "September 2023"
        location: "Berkeley, CA"
        logo: <img src="../images/berkeley.png" alt="Berkeley logo" height="125px" class="education-logo">
        title: "Product Management Program Certificate<br>UC Berkeley Haas School of Business"
        descriptions:
          - "Intensive program focused on end-to-end product management methodologies, from ideation to market launch"
          - "Developed expertise in customer discovery, market analysis, product strategy, and agile development practices"
          - "Created product roadmaps and go-to-market strategies through hands-on projects and real-world case studies"
          - "Collaborated with cross-functional teams to define product requirements, prioritize features, and deliver value propositions"
      - timePeriod: "June 2016 - November 2020"
        location: "Cambridge, MA & Seattle, WA"
        logo: <img src="../images/alexa.png" alt="Alexa logo" height="150px" class="company-logo">
        title: "Software Development Engineer<br>Alexa AI - Amazon Devices"
        descriptions:
          - Authored clean efficient code in line with company standards following agile methodologies; collaborated with the team to solve complex problems related to model building, testing and release.
          - Migrated language model building services onto AWS to simplify onboarding and user experience for applied scientists
          - Accelerated baseline data collection from control natural language understanding models for metrics used to measure treatment model accuracy improvements for A/B Testing.
          - Designed and built inverse text normalization webapp to convert spoken text into correct written forms to identify search keywords for use by all business verticals.
          - Built search for entity catalogs (e.g., music, devices, skills) on AWS Elasticsearch.
          - Won internal hackathon in the "Best use of Technology" and the "Ship it!" category in 2017 for innovative Alexa skills prototypes.
          - Regularly presented relevant machine learning research papers at the team's journal club.
      - timePeriod: "2014 - 2016"
        location: "Amherst, MA"
        logo: <img src="../images/umass.png" alt="UMass logo" height="125px" class="education-logo">
        title: "MS, Computer Science<br>University of Massachusetts Amherst"
        descriptions:
          - "Specialized in Natural Language Processing and Machine Learning with focus on statistical methods for text analysis and language understanding"
          - "Independent study related to word embeddings for research paper submission reviewer matching for conferences"
          - EMC Student Participation Award to attend Grace Hopper Celebration for Women in Computer Science.
      - timePeriod: "July 2013 - June 2014"
        location: "Bangalore, India"
        logo: <img src="../images/cisco.png" alt="Cisco Systems logo" height="55px" class="company-logo">
        title: "IT Engineer<br>Cloud Orchestration and Platform Services"
        descriptions:
          - Enhanced web administration tools for company-wide resource provisioning
          - Maintained cisco.com and related websites
          - Received "Cisco Star" and "Connected Recognition" awards
      - timePeriod: "2009 - 2013"
        location: "Bangalore, India" 
        logo: <img src="../images/pes_university.png" alt="PES University logo" height="60px" class="education-logo">
        title: "B.E., Computer Science and Engineering<br>PES University"
        descriptions:
          - Graduated with Distinction (all semesters)
---

<style>
.experience-section {
    margin-bottom: 2.5rem;
    padding: 1.5rem;
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.05);
    backdrop-filter: blur(10px);
    transition: transform 0.2s ease-in-out;
}

.experience-section:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.experience-header {
    display: flex;
    align-items: flex-start;
    margin-bottom: 1rem;
    position: relative;
}

.logo-container {
    margin-right: 1.5rem;
    min-width: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.company-logo, .education-logo {
    object-fit: contain;
    margin-right: 1rem;
}

.title-container {
    flex-grow: 1;
    padding-right: 200px; /* Make space for the date and location */
}

.experience-title {
    margin: 0;
    color: var(--md-primary-fg-color);
    font-size: 1.4rem;
    line-height: 1.4;
}

/* Add responsive font size for mobile devices */
@media screen and (max-width: 768px) {
    .experience-title {
        font-size: 1.1rem;
    }
    
    .meta-container {
        position: relative;
        width: 100%;
        text-align: left;
        margin-top: 0.5rem;
    }
    
    .title-container {
        padding-right: 0;
    }
}

.meta-container {
    position: absolute;
    right: 0;
    top: 0;
    text-align: right;
    width: 180px;
}

.experience-period {
    font-size: 1rem;
    color: var(--md-default-fg-color--light);
    margin: 0;
    margin-bottom: 0.25rem;
}

.experience-location {
    font-size: 0.9rem;
    color: var(--md-default-fg-color--light);
    margin: 0;
}

.experience-description {
    margin-left: 1rem;
    padding-left: 1rem;
    border-left: 2px solid var(--md-primary-fg-color--light);
}

.experience-description li {
    margin-bottom: 0.5rem;
    line-height: 1.6;
}
</style>

# Professional Experience

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/aws.png" alt="AWS logo" height="40px" class="company-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">Software Development Engineer<br>AWS Security Assurance</h2>
            <div class="meta-container">
                <p class="experience-period">June 2025 - Present</p>
                <p class="experience-location">Seattle, WA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Lead development of security assessment and compliance automation tools that help AWS services exceed the security and compliance expectations of regulators, auditors, and customers globally.</li>
            <li>Design and implement scalable solutions that stand up to the scrutiny of external regulators and inspection by AWS's most security-sensitive customers.</li>
            <li>Collaborate with a multidisciplinary team of software engineers, security engineers, technical product/program managers, data engineers, and compliance specialists to build customer trust through innovative security solutions.</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/amazon.png" alt="Amazon logo" height="40px" class="company-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">Software Development Engineer and Research Engineer<br>Applied AI - Amazon Worldwide Stores</h2>
            <div class="meta-container">
                <p class="experience-period">August 2022 - January 2025</p>
                <p class="experience-location">Bellevue, WA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Identified customer pain points, explored relevant recent research addressing similar challenges, developed proof of concept or minimally viable/lovable product, iterated on prototype, and conducted user acceptance tests for Human-in-the-loop tools like Computer Vision Annotation Tool (CVAT) and AWS Sagemaker Groundtruth for Prime Air data annotations.</li>
            <li>Developed a geocode verification prototype using AWS Bedrock Agents that mirrors auditor workflows by integrating external APIs (Bing, ESRI, HereMaps) for Last Mile Analytics. The initial phase achieved promising accuracy and recall on curated groundtruth data, helping shape the future project roadmap.</li>
            <li>Led comprehensive security and privacy reviews for handling classified customer data to meet industry compliance standards Earned the "Mission Impossible" award for rapidly building customer trust through security implementations with agile. Managed service-level security certifications for a 40+ person organization and shared best practices across teams. Additionally, implemented security measures for a worldwide fulfillment center stowing and shelf recognition automation project, contributing to an $8.8MM YoY reduction in cost to serve.</li>
            <li>Co-led product development for SmartSifting, a model training accelerator library achieving up to 35% efficiency gains, through creating whitepapers, presentations, press releases, and FAQs. Incorporated private beta feedback from major AWS customers to improve user experience before launching in the AWS Sagemaker Deep Learning Container.</li>
            <li>Cut experimentation setup time by 50% for science teams working on AI agents by implementing an experiment harness on AWS Sagemaker Studio and providing targeted documentation.</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/uw.png" alt="UW logo" height="125px" class="education-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">MBA, Technology Management<br>University of Washington Foster School of Business</h2>
            <div class="meta-container">
                <p class="experience-period">2023 - 2026 (Expected)</p>
                <p class="experience-location">Seattle, WA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Coursework in Strategic Management of Technology & Innovation, focusing on dynamics of tech-driven industries and frameworks for managing technology-intensive businesses</li>
            <li>Advanced studies in Entrepreneurship and Customer Experience Strategy, including venture creation, startup financing, and CX methodology</li>
            <li>Specialized training in Tools for analytics-driven business insights</li>
            <li>Leadership development through courses in Ethical Leadership, Leading Organizational Change, and Building Effective Teams</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/berkeley.png" alt="Berkeley logo" height="125px" class="education-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">Product Management Program Certificate<br>UC Berkeley Haas School of Business</h2>
            <div class="meta-container">
                <p class="experience-period">September 2023</p>
                <p class="experience-location">Berkeley, CA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Intensive program focused on end-to-end product management methodologies, from ideation to market launch</li>
            <li>Developed expertise in customer discovery, market analysis, product strategy, and agile development practices</li>
            <li>Created product roadmaps and go-to-market strategies through hands-on projects and real-world case studies</li>
            <li>Collaborated with cross-functional teams to define product requirements, prioritize features, and deliver value propositions</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/alexa.png" alt="Alexa logo" height="150px" class="company-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">Software Development Engineer<br>Alexa AI - Amazon Devices</h2>
            <div class="meta-container">
                <p class="experience-period">June 2016 - November 2020</p>
                <p class="experience-location">Cambridge, MA & Seattle, WA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Authored clean efficient code in line with company standards following agile methodologies; collaborated with the team to solve complex problems related to model building, testing and release.</li>
            <li>Migrated language model building services onto AWS to simplify onboarding and user experience for applied scientists</li>
            <li>Accelerated baseline data collection from control natural language understanding models for metrics used to measure treatment model accuracy improvements for A/B Testing.</li>
            <li>Designed and built inverse text normalization webapp to convert spoken text into correct written forms to identify search keywords for use by all business verticals.</li>
            <li>Built search for entity catalogs (e.g., music, devices, skills) on AWS Elasticsearch.</li>
            <li>Won internal hackathon in the "Best use of Technology" and the "Ship it!" category in 2017 for innovative Alexa skills prototypes.</li>
            <li>Regularly presented relevant machine learning research papers at the team's journal club.</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/umass.png" alt="UMass logo" height="125px" class="education-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">MS, Computer Science<br>University of Massachusetts Amherst</h2>
            <div class="meta-container">
                <p class="experience-period">2014 - 2016</p>
                <p class="experience-location">Amherst, MA</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Specialized in Natural Language Processing and Machine Learning with focus on statistical methods for text analysis and language understanding</li>
            <li>Independent study related to word embeddings for research paper submission reviewer matching for conferences</li>
            <li>EMC Student Participation Award to attend Grace Hopper Celebration for Women in Computer Science.</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/cisco.png" alt="Cisco Systems logo" height="55px" class="company-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">IT Engineer<br>Cloud Orchestration and Platform Services</h2>
            <div class="meta-container">
                <p class="experience-period">July 2013 - June 2014</p>
                <p class="experience-location">Bangalore, India</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Enhanced web administration tools for company-wide resource provisioning</li>
            <li>Maintained cisco.com and related websites</li>
            <li>Received "Cisco Star" and "Connected Recognition" awards</li>
        </ul>
    </div>
</div>

<div class="experience-section">
    <div class="experience-header">
        <div class="logo-container">
            <img src="../images/pes_university.png" alt="PES University logo" height="60px" class="education-logo">
        </div>
        <div class="title-container">
            <h2 class="experience-title">B.E., Computer Science and Engineering<br>PES University</h2>
            <div class="meta-container">
                <p class="experience-period">2009 - 2013</p>
                <p class="experience-location">Bangalore, India</p>
            </div>
        </div>
    </div>
    <div class="experience-description">
        <ul>
            <li>Graduated with Distinction (all semesters)</li>
        </ul>
    </div>
</div> 