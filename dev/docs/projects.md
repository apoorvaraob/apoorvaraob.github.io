---
title: Projects
---

# Featured Projects

## Geocode Verification System
<div class="project-card">
    <div class="project-content">
        <h3>Overview</h3>
        <p>An AI-powered verification system using AWS Bedrock Agents for validating location data.</p>
        
        <h3>Key Features</h3>
        <ul>
            <li>Multi-API integration (Bing, ESRI, HereMaps)</li>
            <li>High accuracy and recall on groundtruth data</li>
            <li>Robust security measures for sensitive data</li>
            <li>Scalable architecture for large-scale processing</li>
        </ul>
        
        <h3>Technologies</h3>
        <div class="tech-stack">
            <span class="tech-tag">AWS Bedrock</span>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">REST APIs</span>
            <span class="tech-tag">GIS</span>
        </div>
    </div>
</div>

## Computer Vision Annotation Tool
<div class="project-card">
    <div class="project-content">
        <h3>Overview</h3>
        <p>Mentored and provided architectural oversight for the enhancement of CVAT (Computer Vision Annotation Tool) for Prime Air data annotations with human-in-the-loop workflows.</p>
        
        <h3>Leadership & Mentorship</h3>
        <ul>
            <li>Provided technical mentorship and architectural guidance to the lead developer</li>
            <li>Reviewed and guided the implementation of human-in-the-loop workflows</li>
            <li>Oversaw user acceptance testing strategy and execution</li>
            <li>Advised on performance optimization approaches for large-scale data processing</li>
            <li>Directed UI/UX improvements to enhance annotator productivity</li>
        </ul>
        
        <h3>Technologies</h3>
        <div class="tech-stack">
            <span class="tech-tag">CVAT</span>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">Computer Vision</span>
            <span class="tech-tag">React</span>
        </div>
    </div>
</div>

## SmartSifting - Model Training Accelerator
<div class="project-card">
    <div class="project-content">
        <h3>Overview</h3>
        <p>A model training accelerator library achieving 35% efficiency gains in AWS SageMaker Deep Learning Container.</p>
        
        <h3>Key Achievements</h3>
        <ul>
            <li>Led product development and strategy</li>
            <li>Collaborated with AWS customers during private beta</li>
            <li>Created comprehensive documentation including whitepapers and technical guides</li>
            <li>Successfully integrated with AWS Sagemaker Deep Learning Container</li>
        </ul>
        
        <h3>Technologies</h3>
        <div class="tech-stack">
            <span class="tech-tag">Python</span>
            <span class="tech-tag">AWS SageMaker</span>
            <span class="tech-tag">Deep Learning</span>
            <span class="tech-tag">Docker</span>
        </div>
    </div>
</div>

## Inverse Text Normalization System
<div class="project-card">
    <div class="project-content">
        <h3>Overview</h3>
        <p>A web application for converting spoken text to written forms with search keyword identification.</p>
        
        <h3>Features</h3>
        <ul>
            <li>RESTful API design for seamless integration</li>
            <li>Multi-vertical business keyword identification</li>
            <li>Scalable AWS infrastructure deployment</li>
            <li>High-performance text processing engine</li>
        </ul>
        
        <h3>Technologies</h3>
        <div class="tech-stack">
            <span class="tech-tag">NLP</span>
            <span class="tech-tag">AWS</span>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">REST APIs</span>
        </div>
    </div>
</div>

<style>
.project-card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    margin: 2rem 0;
    padding: 2rem;
    transition: transform 0.2s, box-shadow 0.2s;
}

.project-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project-content h3 {
    color: var(--primary-color);
    margin: 1rem 0 0.5rem 0;
    font-size: 1.5rem;
}

.project-content p {
    font-size: 1rem;
    line-height: 1.6;
    margin-bottom: 1rem;
}

.project-content ul {
    list-style-type: none;
    padding: 0;
}

.project-content li {
    margin: 0.75rem 0;
    padding-left: 1.5rem;
    position: relative;
    font-size: 1rem;
    line-height: 1.5;
}

.project-content li::before {
    content: '•';
    position: absolute;
    left: 0;
    color: var(--primary-color);
}

.tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 1rem;
}

.tech-tag {
    background: var(--section-bg-color);
    color: var(--primary-color);
    padding: 0.25rem 0.75rem;
    border-radius: 16px;
    font-size: 0.9rem;
}

/* Mobile Responsive Styles */
@media (max-width: 768px) {
    .project-card {
        padding: 1.25rem;
        margin: 1.5rem 0;
    }
    
    .project-content h3 {
        font-size: 1.25rem;
        margin: 0.75rem 0 0.5rem 0;
    }
    
    .project-content p {
        font-size: 0.95rem;
        line-height: 1.5;
    }
    
    .project-content li {
        font-size: 0.95rem;
        margin: 0.5rem 0;
        padding-left: 1.25rem;
    }
    
    .tech-tag {
        font-size: 0.85rem;
        padding: 0.2rem 0.6rem;
    }
}

/* Small Mobile Devices */
@media (max-width: 480px) {
    .project-card {
        padding: 1rem;
        margin: 1rem 0;
    }
    
    .project-content h3 {
        font-size: 1.1rem;
    }
    
    .project-content p,
    .project-content li {
        font-size: 0.9rem;
    }
    
    .tech-tag {
        font-size: 0.8rem;
        padding: 0.15rem 0.5rem;
    }
    
    .tech-stack {
        gap: 0.35rem;
    }
}
</style> 