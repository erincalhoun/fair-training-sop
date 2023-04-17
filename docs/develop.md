# Development of FAIR training materials

## 1. Introduction
### Why should training materials be FAIR?

Making training materials FAIR is essential for ensuring that they can be easily found, accessed, and used. Adhering to FAIR principles not only broadens your potential audience but also facilitates collaboration and resource sharing, making the development process more efficient.

### Key considerations
**Findability**

Use descriptive titles, relevant keywords and controlled vocabularies (EDAM) where possible, rich metadata (BioSchemas), and a clear organizational structure.

**Accessibility**

Define access rules from the beginning, provide alt-text wherever possible, and offer comprehensive instructions for required tools or resources.

**Interoperability**

Adopt open platforms and formats, use standard domain-specific language, and follow best practices for content organization.

**Reusability**

Design your materials in a way that allows for easy adaptation and customization, and provide clear instructions for use and attribution.

!!! tip

    Useful links:

    **Bioschemas tutorial**

    - [How to mark up your own resource](https://bioschemas.org/tutorials/howto/howto_add_markup)
    - [Adding markup to a GitHub Pages site](https://bioschemas.org/tutorials/howto/howto_add_github)

    **Bioschemas profiles**

    - [Course](https://bioschemas.org/profiles/Course/1.0-RELEASE)
    - [CourseInstance](https://bioschemas.org/profiles/CourseInstance/1.0-RELEASE)
    - [TrainingMaterial](https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE)

    **EDAM: Bioscientific data analysis ontology**

    - [EBI Ontology Look-up Service OLS](https://www.ebi.ac.uk/ols/ontologies/edam)
    - [EDAM browser](https://edamontology.github.io/edam-browser/#topic_0091)
    - [EDAM documentation](https://edamontologydocs.readthedocs.io/en/latest/index.html)

## 2. A comprehensive lesson plan
### Describe the materials appropriately
**Use clear, descriptive titles.**

The title should accurately reflect the content and help users quickly understand what's covered.

**List relevant keywords.**

Select keywords commonly used in your field and relevant to the subject matter (EDAM) to help users find them when searching online or within a repository.

### Identify the target audience
Clearly define your target audience so trainees can determine if the materials are:
- relevant to their needs
- at an appropriate level

Describe the specific topics covered and how they relate to the intended audience's professional interests or research areas. Indicate the level of complexity or expertise required, preferably with specific terms, for example with [EBI's Competency Hub](https://competency.ebi.ac.uk/develop-your-courses).
### Specify prerequisites
**Knowledge:**

Specify concepts that are required to understand the material, but won't be covered.

**Skills:**

List skills or techniques that trainees should be familiar with.

**Tools:**

Clearly indicate tools or software required to use the materials, and provide links and detailed instructions.
### Define SMART learning outcomes
Use SMART principles to express the knowledge, skills, and abilities (KSAs) trainees will acquire.

**Specific:**

Define KSAs concisely. Avoid compound learning outcomes.

**Measurable:** 

Use action verbs (see Bloom's taxonomy for examples) to describe learning outcomes in a way that allows for assessment.

**Achievable:**

Ensure learning outcomes are realistic given the scope and duration of the training.

**Relevant:**

Align the learning outcomes with the needs and interests of your target audience.

**Time-bound:**

Indicate the expected timeframe for achieving learning outcomes.

### Detail the learning experiences
Outline the types of learning experiences included in your materials and provide a brief description with any necessary links.

**Lectures:**

Describe the content and link to slides, recordings, or transcripts.

**Tutorials:**

Provide a summary of the task, along with instructions and required resources.

**Exercises:**

List exercises or assignments you expect trainees to complete and include their purpose and expected outcomes.

**Group work:**

Detail planned collaborative activities and offer guidance on how groups will be formed and interact.

### Estimate time requirements
Estimate the total time required to complete training, including all lectures, tutorials, exercises, and group work. 
Further break down time needed for each section/module as well as exercises, allowing trainees to plan their learning experience effectively.
### Incorporate instructor notes
Include instructor notes for context and reusability.

**Feedback and modifications:**

Detail prior feedback and resulting modifications to the materials.

**Technical tips:**

Offer guidance on optimizing tutorials and exercises. Include a troubleshooting section if necessary.

**Challenges:**

Address frequently encountered problems and suggest solutions or alternatives.

**Essential sections:**

Identify core and optional sections, allowing trainers and trainees to prioritize learning based on needs and time constraints.
## 3. Select a development platform
### Ideal features
Ideally the platform should:

- be open source
- encourage collaboration
- offer version control to maintain a history of updates
### Options for development
**Locally**

Create and store training materials on your local computer or internal drives using familiar software like Microsoft Office. While local development feels convenient, it can be challenging to collaborate FAIRly and share the materials with others.

**Repositories**

Repositories (like GitHub) that offer versioning enable you to create, edit, and store your training materials online (openly or restricted). These features facilitate collaboration, tracking changes, and sharing.

**Online platforms**

Online platforms can be propriety (Google Suite) or open source (Moodle). Both allow you to develop, collaborate on, and share your training materials online. The platforms are more customizeable, often including additional features like real-time editing and chat.
## 4. Choose suitable formats
### Common formats
**Slides:**

OpenDocument presentations (.odp), Google Slides, Microsoft PowerPoint (.pptx), Apple Keynote (.key)

**Documents:**

OpenDocument text (.odt), Google Docs, Microsoft Word (.docx), PDF

**Markup:**

Markdown, HTML, XML

**Multimedia:**

Many formats (MP4, WebM, MKV) and hosting platforms (YouTube, Vimeo)

### Assessing and improving FAIRness
**Slides:**

Slides can be findable and accessible when they:
- include descriptive metadata including titles and keywords
- focus on accessibility (clean design, alt-text, reading order for screen readers)
- are shared on an appropriate platform

However, slides may not be as easily interoperable as other formats and require extra content for reusability.

To improve interoperability, consider using an open format like .odp.

To improve reusability, the slides should contain:
- author/contributor information
- a license for reuse
- proper citations for all borrowed content
- notes for context, especially for images
- a transcript of the accompanying lecture/presentation

**Documents:**

PDFs are highly portable and accessible for most, but their static nature and commonly licensed software limits interoperability and reusability. Include the original format alongside PDFs to make them more FAIR.

**Markup:**

Markdown files are highly findable, accessible, interoperable, and reusable, as they easily convert to other formats and can be read by both humans and machines. HTML may require additional effort to make content reusable, such as providing downloadable source files or templates. 

Increase findability by following best practices for web accessibility and including EDAM keywords/Bioschemas profile.

**Multimedia:**

Videos and audio can be findable and accessible when properly described and hosted on accessible platforms but have limited interoperability and reusability. Create short videos covering single topics and consider providing captions, transcripts, or other supplementary materials to enhance FAIRness.