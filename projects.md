---
layout: page
title: Projects
subtitle: A showcase of my software engineering work
---

<div class="projects-list">
    {% for project in site.projects %}
    <div class="project-item">
        <div class="project-header">
            <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
            <div class="project-meta">
                {% if project.github_url %}
                <a href="{{ project.github_url }}" class="project-link" target="_blank">
                    <i class="fab fa-github"></i> View on GitHub
                </a>
                {% endif %}
                {% if project.demo_url %}
                <a href="{{ project.demo_url }}" class="project-link" target="_blank">
                    <i class="fas fa-external-link-alt"></i> Live Demo
                </a>
                {% endif %}
            </div>
        </div>
        
        <div class="project-content">
            {{ project.excerpt }}
            
            {% if project.technologies %}
            <div class="project-technologies">
                <strong>Technologies:</strong>
                {% for tech in project.technologies %}
                <span class="tech-tag">{{ tech }}</span>
                {% endfor %}
            </div>
            {% endif %}
        </div>
        
        <div class="project-footer">
            <a href="{{ project.url | relative_url }}" class="btn btn-outline">Read More</a>
        </div>
    </div>
    {% endfor %}
</div>

{% if site.projects.size == 0 %}
<div class="no-projects">
    <h3>Projects Coming Soon</h3>
    <p>I'm currently working on documenting my projects. Check back soon for updates!</p>
</div>
{% endif %}
