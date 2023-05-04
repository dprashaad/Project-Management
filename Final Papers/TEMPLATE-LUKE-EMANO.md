## Audition: An Open-Source Platform for Building Bands
Luke Emano; IS 340 Spring 2023

### Abstract
This paper aims to address the challenges that musicians and singers face when finding band members to collaborate and perform with. With a highly competitive and oversaturated music industry, finding the right fit in terms of musical style, personality, availability, and logistical issues are some significant problems that need to be solved. To address these challenges, this paper outlines the management of a project called Audition, an open-source platform where musicians and singers can create a profile, list their preferences and previous work, and search for potential band members. This platform targets musicians and singers looking to form or join a band and uses a tech stack consisting of ReactJS, Node.js, and AWS. Other open-source principles mentioned in this paper derive from the topics discussed in IS 340 over the Spring 2023 semester.
### Introduction
Music is an art form that has the power to bring people together and create a sense of community. For musicians and singers, playing and performing music is often a way to connect with others who share their passion. However, one of the most prominent challenges musicians and singers face is finding the right band members to collaborate and perform with. Finding and auditioning potential band members can be time-consuming and frustrating, often leading to limited success. One of the biggest challenges in finding band members is that the music industry is highly competitive and oversaturated. With so many talented musicians and singers vying for limited opportunities, it can be difficult for individuals to stand out and be noticed [1]. Additionally, finding the right fit regarding musical style, personality, and availability can be daunting. Many musicians and singers must rely on word of mouth or social media to find potential band members, which can lead to limited success. Another challenge in finding band members is the audition process; auditions can be intimidating and nerve-wracking for both the performer and the potential band members. It can be challenging for musicians and singers to showcase their skills in a brief audition, and it can be equally difficult for the band to assess whether the performer fits their group. This difficulty is not just limited to individual musicians and singers, but it is also a challenge for bands that are looking to expand or replace members. For established bands, finding the right member to replace someone who has left can be a difficult process. The new member needs to fit in with the band's dynamic and style, and the band needs to assess whether the new member will be able to contribute to the group's success. When going about it traditionally, auditions are often a one-time event, meaning musicians and singers may have multiple auditions before finding the right band. Logistical issues can also exacerbate the challenge of finding band members. For example, musicians and singers may have to travel long distances for auditions, which can be expensive and time-consuming. Altogether, finding the right band members is a significant challenge for musicians and singers, and it can be frustrating and time-consuming. However, technology is providing solutions to these challenges, with web applications such as Audition helping musicians and singers connect with potential band members more quickly and efficiently.
### Purpose
The purpose of Audition is to promote creative output from bands and help stimulate new forms of music. As mentioned above, music is powerful, bringing people together and creating a sense of community. By reducing the friction many musicians and vocalists face when building a band, these artists can more easily share their music with the world. Audition would work very similar to a social media platform; firstly, users would create a profile of their previous work, which may include previous music they have covered or composed, gigs they have performed at, or any other content that demonstrates their musical abilities. Within their profile, they could list their band preferences: the type of music they are looking to play in a band, instrument/vocal requirements, and the number of members they are looking for. Each user's profile will be listed in a public feed, and once a user finds a potential band member, they can message that user and request them to audition for the band by covering a particular song or demonstrating their abilities; these auditions can either be live or pre-recorded according to the auditioner's desires. 

Audition will initially start as a web-based application and eventually support mobile platforms; this is important because mobile apps are highly accessible to a large population of users, and our goal is to help streamline the audition process so users can audition essentially anytime, anywhere. Additionally, our platform will be open-source, a beneficial strategy for a group-based social platform like Audition because open-source software is typically developed collaboratively by a community of developers, meaning that bugs and issues can be quickly identified and resolved by a large group of people with diverse skill sets [2]. This can also lead to faster and more efficient development and a more stable and trustworthy platform. Additionally, open-source software is typically freely available and adjustable, which can encourage innovation and customization by developers and users alike. Finally, open-source software can promote transparency and accountability, as the code is available for anyone to inspect and audit. Beyond just creating Audition as an open-source project, we hope this project will inspire developers to modify the code for other group-based endeavors requiring certain qualifications, such as team sports or extreme adventures.
### Target Audience
The ideal target audience for Audition are musicians and singers looking to form or join a band. This may include individuals who are new to a particular area and looking to connect with other musicians, as well as experienced musicians seeking new band members to collaborate with. According to a study by the National Endowment for the Arts, approximately 1 in 10 American adults play a musical instrument, with the guitar being the most popular instrument. Additionally, the study found that participation in music declines with age, with young adults (ages 18-24) being the most likely to play an instrument [3]. This suggests that a large pool of potential musicians is available for forming bands but that competition may be fiercer in specific age ranges or musical genres. In particular, Audition may first be of interest to college students, most of whom are between 18-24, who are more likely to play a musical instrument and be interested in forming a band. Audition may also appeal to individuals who need help finding band members due to a lack of local music scene or limited social networks.
### Strategy
The tech stack for Audition will consist of a modern web application framework, a database, and a cloud hosting platform. I plan to use ReactJS, Node.js as our database and AWS for cloud hosting. ReactJS is one of the most popular front-end libraries that allow developers to build dynamic and interactive user interfaces using a component-based approach, enabling developers to reuse code and easily build complex interfaces. Due to its reputation and highly-supported ecosystem, ReactJS has a robust set of tools and documentation that simplifies the development process. It is ideal for open-source projects where multiple developers may be contributing code. Additionally, ReactJS integrates smoothly with React Native, the framework used for mobile development that is an extension of ReactJS, allowing for streamlined scalability to mobile in the future [4]. React Native also comes with cross-platform integration, allowing both android and ios devices access to Audition as a mobile application. Node.js, on the other hand, is a popular back-end framework that provides a scalable and high-performance environment for developing server-side applications. Like ReactJS, Node.js also has a large and active community of developers contributing to its ecosystem, making it easier to find resources, plugins, and tools to help with development [5]. AWS provides a reliable and secure cloud infrastructure that can be used to host and deploy open-source applications. It offers a wide range of services, including computing, storage, and database services and tools for monitoring and scaling applications. Using AWS for an open-source project can help ensure the application is scalable, reliable, and secure, which is crucial for maintaining the community's trust [6].

Git will be used for version control with the code repository hosted on GitHub, the leading version control system currently on the market. GitHub is the best version control system for open-source projects due to its collaborative and user-friendly features that allow developers to easily share code, track changes, and collaborate with others, making it easier for open-source projects to attract contributors and build a community. Its popularity and widespread use also mean that developers are already familiar with the platform, making it easier to onboard new contributors to the project. For project management, Notion will be used. Notion is a management tool that allows users to create a centralized workspace where project information, documentation, and tasks can be easily organized and accessed by all members of the team. Notion also offers a flexible and customizable interface that can be tailored to fit the specific needs of the project, in addition to its collaboration features that allow team members to work together seamlessly by leaving comments, tagging team members, and assigning tasks. Notion's integrations with other popular tools, such as GitHub and Google Drive further simplify the project management process. Overall, Notion provides an all-in-one solution for managing open-source projects, making it a powerful and effective tool for project management [7].

Audition will be licensed under the Apache License 2.0, an open-source license that allows users to use, modify, distribute, and redistribute open-source software, both commercially and non-commercially, without having to worry about any potential legal issues. It also protects us, the original developers, by requiring that any modifications to the code be clearly marked and attributed to us. One of the key benefits of the Apache License 2.0 is that it is compatible with other open-source licenses, which allows Audition to integrate with other open-source software without any legal conflicts. The license also provides explicit patent protection, which helps protect the project from legal disputes related to patents [8]. Overall, the Apache License 2.0 balances permissive and protective, making it a good choice for open-source projects like Audition.

### Community
To create a structure for the lead development team behind Audition, we will be hosting two meetings weekly– Tuesdays and Fridays– for one hour each. Tuesday meetings will act as a "town hall" meeting where all project participants will come together to discuss the project roadmap, contributing guidelines, technical bugs or issues, community management, and sustainability. The project roadmap is an opportunity to share the project's vision, goals, and milestones and get feedback and suggestions from the open-source community. Community guidelines are essential to clarify how developers can contribute to the project, including code quality, documentation, and testing guidelines. If the project faces technical challenges or issues, a town hall meeting can be a great forum to discuss these challenges and brainstorm solutions. This can help build community engagement and collaboration and ensure the project stays on track. Additionally, building and maintaining a strong community is critical for the success of an open-source project; a town hall meeting can be an opportunity to discuss community management strategies, such as communication channels, code of conduct, and event planning. Open-source projects also require ongoing support and resources to thrive, so a town hall meeting can be a place to discuss fundraising, sponsorships, and partnerships. This can help ensure the project remains viable and sustainable in the long term. The other meeting will consist of an open workspace for all or any developers to come together and work on the project synchronously. These two meetings are hoped to work in tandem with one another to keep engagement in the community consistent and regular for continued development.

As these weekly meetings occur, numerous community events are planned to be hosted throughout the year, offering a fun and engaging way to connect the Audition open-source community, typically composed of like-minded individuals who share a passion for music. One such event is the annual Music Hackathon which brings together musicians, developers, and music enthusiasts to collaborate on innovative music-related projects. Participants have 24 hours to create and present their projects, which range from music visualization tools to new ways of generating sounds and beats, and help build the bridge between music and technology [9]. Another fun community event for the open-source community is the Maker Faire, a gathering of makers, creators, and innovators from all walks of life. This event features a range of musical performances, interactive installations, and workshops that allow participants to experiment with different musical technologies and instruments. Attendees can try building their own musical instruments, learn how to code music using open-source software, or simply listen to some fantastic live performances [10]. This is another great event for the community as it can provide other ideas to implement in Audition or its derivatives. For those interested in a more casual and relaxed environment, plenty of open jam sessions and music meetups can be hosted throughout the year to offer an opportunity to play and jam with other musicians. These events are a great way to network with other developers and musicians and can often lead to new collaborations and creative projects. Whether someone is an experienced musician or just starting, there is always something to learn and enjoy at these community events while strengthening the passion that goes into Audition or similar projects.
### Conclusion
In conclusion, finding the right band members is a significant challenge for musicians and singers, and it can be frustrating and time-consuming. However, with the advancement of technology, solutions like Audition can help reduce the friction many artists face when building a band. By leveraging the benefits of open-source software and promoting transparency and accountability, Audition has the potential to become a widely adopted platform in the music industry. Overall, the implementation of Audition can bring more musicians and singers together, facilitate the formation of bands, and ultimately create more opportunities for artists to share their music with the world.

## References

IFPI GLOBAL MUSIC REPORT 2021. (n.d.). https://gmr2021.ifpi.org/report

Panel, E. (2021, August 6). 17 Industry Leaders Share Pros And Cons Of Tapping Into Open-Source Code. Forbes. https://www.forbes.com/sites/forbestechcouncil/2021/08/06/17-industry-leaders-share-pros-and-cons-of-tapping-into-open-source-code/?sh=202ab0dc3de3

National Endowment for the Arts Releases Latest Survey of Public Participation in the Arts. (2020b, January 22). National Endowment for the Arts. https://www.arts.gov/news/press-releases/2020/national-endowment-arts-releases-latest-survey-public-participation-arts 

React. (n.d.). https://react.dev/

About | Node.js. (n.d.). Node.js. https://nodejs.org/en/about

Cloud Computing Services - Amazon Web Services (AWS). (n.d.). Amazon Web Services, Inc. https://aws.amazon.com/

Your wiki, docs & projects. Together. (n.d.). Notion. https://www.notion.so/product

Apache License, Version 2.0. (n.d.). https://www.apache.org/licenses/LICENSE-2.0.html

Remote Music Hackathon, May 23rd. (n.d.). https://remotemusichackathon.splashthat.com/

makerfaire.com - Maker Faire. (2023, April 28). Maker Faire. https://makerfaire.com/