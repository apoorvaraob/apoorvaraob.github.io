---
title: Skills
---

# Skills & Expertise

<div class="skills-container">
    <div class="skill-category">
        <h2><i class="fas fa-tasks"></i> Product Management</h2>
        <div class="skill-grid">
            <div class="skill-item">
                <h3>Strategy & Planning</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Product Strategy</span>
                    <span class="skill-tag">Roadmapping</span>
                    <span class="skill-tag">Market Analysis</span>
                    <span class="skill-tag">Competitive Analysis</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>User Research</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Customer Discovery</span>
                    <span class="skill-tag">User Interviews</span>
                    <span class="skill-tag">Usability Testing</span>
                    <span class="skill-tag">A/B Testing</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Agile & Scrum</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Sprint Planning</span>
                    <span class="skill-tag">Backlog Management</span>
                    <span class="skill-tag">Scrum Master</span>
                </div>
            </div>
        </div>
    </div>

    <div class="skill-category">
        <h2><i class="fas fa-users"></i> Leadership & Soft Skills</h2>
        <div class="skill-grid">
            <div class="skill-item">
                <h3>Team Management</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Cross-functional Leadership</span>
                    <span class="skill-tag">Mentoring</span>
                    <span class="skill-tag">Team Building</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Communication</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Stakeholder Management</span>
                    <span class="skill-tag">Technical Writing</span>
                    <span class="skill-tag">Public Speaking</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Problem Solving</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Strategic Thinking</span>
                    <span class="skill-tag">Critical Analysis</span>
                    <span class="skill-tag">Innovation</span>
                </div>
            </div>
        </div>
    </div>

    <div class="skill-category">
        <h2><i class="fas fa-code"></i> Technical Skills</h2>
        <div class="skill-grid">
            <div class="skill-item">
                <h3>Programming Languages</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Python</span>
                    <span class="skill-tag">Java</span>
                    <span class="skill-tag">JavaScript</span>
                    <span class="skill-tag">SQL</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Machine Learning</h3>
                <div class="skill-tags">
                    <span class="skill-tag">TensorFlow</span>
                    <span class="skill-tag">PyTorch</span>
                    <span class="skill-tag">NLP</span>
                    <span class="skill-tag">Computer Vision</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Cloud & Infrastructure</h3>
                <div class="skill-tags">
                    <span class="skill-tag">AWS Services</span>
                    <span class="skill-tag">Docker</span>
                    <span class="skill-tag">CI/CD</span>
                </div>
            </div>
            <div class="skill-item">
                <h3>Data Analysis</h3>
                <div class="skill-tags">
                    <span class="skill-tag">Pandas</span>
                    <span class="skill-tag">Data Visualization</span>
                </div>
            </div>
        </div>
    </div>

    <div class="skill-category">
        <h2><i class="fas fa-certificate"></i> Certifications</h2>
        <div class="certifications">
            <div class="cert-item">
                <i class="fas fa-award"></i>
                <h3>Product Management</h3>
                <p>UC Berkeley Haas School of Business</p>
            </div>
        </div>
    </div>
</div>

<style>
.skills-container {
    max-width: 1200px;
    margin: 0 auto;
}

.skill-category {
    background: white;
    border-radius: 8px;
    padding: 2rem;
    margin: 2rem 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.skill-category h2 {
    color: var(--primary-color);
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
}

.skill-item {
    background: var(--section-bg-color);
    padding: 1.5rem;
    border-radius: 8px;
}

.skill-item h3 {
    color: var(--text-color);
    margin-bottom: 1rem;
    font-size: 1.1rem;
}

.skill-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
}

.skill-tag {
    background: white;
    color: var(--primary-color);
    padding: 0.25rem 0.75rem;
    border-radius: 16px;
    font-size: 0.9rem;
    transition: transform 0.2s;
}

.skill-tag:hover {
    transform: translateY(-2px);
}

.certifications {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
}

.cert-item {
    text-align: center;
    padding: 1.5rem;
    background: var(--section-bg-color);
    border-radius: 8px;
    transition: transform 0.2s;
}

.cert-item:hover {
    transform: translateY(-2px);
}

.cert-item i {
    font-size: 2rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
}

.cert-item h3 {
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.cert-item p {
    color: #666;
    font-size: 0.9rem;
}

@media (max-width: 768px) {
    .skill-category {
        padding: 1.5rem;
    }

    .skill-grid {
        grid-template-columns: 1fr;
        gap: 1rem;
    }

    .skill-item {
        padding: 1rem;
    }

    .certifications {
        grid-template-columns: 1fr;
    }
}
</style> 