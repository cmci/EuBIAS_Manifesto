<h1>EuBIAS Manifesto</h1>

<p>Date: June 19, 2013</p>

<p>Authors: Kota Miura, Sébastien Tosi, Julien Colombelli</p>

<h2>Introduction</h2>

<p>Bioimaging is an interdisciplinary science. In addition to biology itself, a deep understanding of optics, microscopy, fluorescence probes, image processing and image analysis is required. Due to this overwhelming need of diverse technologies and since it is rather unlikely a single individual can master all these topics, biologists and imaging scientists need to work together to achieve higher scientific goals. In order to facilitate this collaborative process, a strengthening of the bioimaging infrastructure is required. In the following, we focus on the image processing and analysis in bioimaging. We first briefly review the current status of the infrastructure and then explain the need for actions to promote a higher accessibility to bioimage analysis for biological researchers.</p>

<p>Among the overall bioimaging workflow, image processing and analysis come at the very last end. Microscope images are multidimensional data representing complex biological phenomena that involve biochemical reactions occurring within three dimensional spatial contexts. The major task of image processing and analysis is to computationally decrease the dimensionality of the problem under study, extract relevant quantitative information and conduct statistical data analysis.</p>

<p>Compared to the other technologies involved in bioimaging, image processing and analysis is unique in that its infrastructure is essentially made of computational tools. Hardware such as server and client machines, data storages and networks are the physical infrastructure for computation but not the main focus of this meeting. In turn software and its intrinsic capability for simple dissemination is the main target.</p>

<p>To organize and increase  in a scalable way the accessibility to image processing and analysis infrastructure within the European bioimaging community, its heavy dependence on human resource should be given a considerable attention.</p>

<p>Software is a pure product of human imagination. Its availability is solely dependent on the effort of computational scientists and programmers who create algorithms and implement them. We call these individuals “developers”. They create image processing algorithms, design their efficient implementations allowing faster computations, and design graphical user interfaces to simplify the user interactions. The outcome of their efforts ranges from general algorithms that could be used as basis for many types of applications to specific solutions limited to certain biological phenomena. The developers are hence algorithm developers and programmers, but in many cases algorithm developers also take the role of programmers.</p>

<p>As the number of image processing / analysis software and the diversity of image processing / analysis algorithms grew, professional knowledge to combine multiple image processing libraries and tools to construct complex workflows has increasingly become important. For this assembly task, insights in biology, image processing, various computational libraries, computer programming languages and statistics are necessary. Former developers were in many cases taking this role simultaneously, but recently a community of professionals specialized in assembling tools for such customized tasks is growing. They are mostly biologists, engineers and physicists and we will call this new type of professionals “analysts”.</p>

<p>Existing software packages already make available a rich range of tools for processing and analysis of microscope images. They are however constantly evolving and the number of functions is steadily growing. With so many choices offered to the users, the problem to choose the best tool to answer a specific question is not trivial, and sometimes extremely complex. Many high end packages are open source and readily accessible but bridging that accessibility to a specific demand is missing. The enhancement and strengthening of an human network capable of boosting this optimization and allowing a better usage of the existing software through collaborations / consultations / teachings is equally important.
To organize and increase the accessibility to image processing and analysis infrastructure within the European bioimaging community in a scalable way, its heavy dependence on human resource itself should be given with a considerable attention.</p>

<p>For this reason, we briefly overview the activities of developers and analysts. To assess the future of these activities, career paths will also be examined.</p>

<h2>BioImage Community</h2>

<h3>Developers</h3>

<p>Image processing is a solid field where many algorithms have been developed to improve image quality, to extract features, to compress the information, to segment objects, to classify patterns, to track objects, to estimate model parameters in presence of noise and to interactively visualize the data. These advances have been made possible by the interactions between researchers in the field of signal processing, computer vision, mathematics, statistics, machine learning and computer science. Some of these researchers (developers) became specialized in treating microscope images in collaboration with biologists and contributed many software packages and tools (many are also lead by biologists).</p>

<p>These contributions can be seen in a glance in the webpage of the <a href="http://www.openbioimage.org/">Open Bio Image Alliance (OBIA)</a>, as well as the developer on-going gatherings.</p>

<p>Information exchange and human networks have been established through these meetings. The career path of developers inherits that of computer scientists and programmers. Computer scientists have their academic position in computer science, electrical engineering and signal processing departments or image processing position in biological / medical institutes. They publish their outcome of developments in computer science and signal processing journals as well as in biological journals as collaborators, which will be the credit for their scientific career.</p>

<h3>Analysts</h3>

<p>Analysts bridges the gap between developers and biologists. The gap exists since the demands of biologists could ultimately be summarized to "single click and does all". Such automation is possible for some trivial tasks but in many cases the complexity of modern Bioimage Analysis methods hinders the full automation. Every Bioimaging project is unique hence the image analysis, the final step of bioimaging, is also unique and cannot escape from some assembling and customizations. Here analysts come into play to create optimal protocols of image analysis.</p>

<p>In addition to customization of image analysis protocols, another major activity of most of analysts is teaching. Teaching of basics on image processing and analysis techniques shifts up the level of “Image Processing and Analysis literacy” in their belonging institute, which collectively has positive effect in promoting high-level image analysis in that local Bioimaging community.</p>

<p>The analyst is a new type of profession and their number is limited. The first precursory gathering of analysts took a form of course to teach image analysis to biologists in 2013 <a href="www.embl.de/bias2013">(EMBL Master Course on BioImage Data Analysis 2013, BIAS 2013)</a>. The prominent outcome of analysts working together was course textbooks written through collaborative editing and peer reviewing. Through this process, we learned creative ideas from others on how each has been solving various Bioimage Analysis problems. As each of us had been more-or-less working individually and locally, exchange of knowledge were highly valuable and enlightening.</p>

<p>The background of analysts is diverse: Physicists, Computer Scientists, Electrical Engineers, Physical Chemists and Biologists. There is no established career path for becoming analysts, but a need of diverse knowledge as stated already. Compared to developers who have conventional criteria for evaluating their careers, analysts are currently evaluated only by words of mouth. An increased visibility of the their work is required both for stabilizing this new career path and at the same time for the employers to evaluate candidates.</p>

<h3>Users</h3>

<p>Scientists, engineers or students who, in collaboration with analysts or developers, or independently, perform BioImage processing &amp; analysis to ultimately answer scientific questions or support scientific and technological development.</p>

<h2>Tasks</h2>

<p>How could we increase the accessibility and diffusion of image processing / analysis infrastructures, especially in terms of software packages?</p>

<p>Existing software packages already offer a rich and wide range of tools for processing and analysis of microscope images. They are constantly evolving and the number of new functions is steadily growing. With so many options offered to users, the problem for them is now to choose the best tool that matches their needs. In other words, the accessibility is already excellent, but bridging this accessibility to a specific demand is missing. Moreover, the enhancement and strengthening of a human network that can boost the diffusion of the existing software through collaborations / consultations / teachings is equally important.</p>

<p>To overcome the imminent problem that exists as a gap between the availability of software tools and the difficulty of a specific choice, the flow of information could be smoothed from multiple angles. At the same time staging the role of “analysts” at the community level will be key. For these reasons, we propose the following actions:</p>

<h3>A Web Tool</h3>

<p>A list of links to software packages could be found in various sources, but from the user side this is not really practical because in actual research scenarios we want to find a specific function that matches the need regardless of the package in which it is contained. Many software packages are developed as a unit, so their documentations are monolithic. The list and associated documentations should become more functional rather than a one-dimensional listing of package names.</p>

<p>A web platform that integrates all  documentations should be created. It could decrease perpetual “reinventions of the wheel” and may at the same time channel the new developments towards truly innovative extensions. We call such user-oriented functional and highly interactive web platform as a “web tool” and propose the following specifications:</p>

<ol>
<li>One page per Function

<ol type="a">
<li>Users try to find functions based on their needs rather than by name of the software package. This means that each function (plugin, menu item) included in the software packages should be assigned a single documentation page, and ideally should not be categorized by package.</li>
<li>This is partially actualized in the Fiji project wiki page, where each contributed plugin features a page listing the name of the developer, the link to the source code and the usage instructions. This way of documentation should be extended to include all software packages and presented as single web document that offers higher accessibility to users.</li>
</ol>
</li>
<li>Multiple tagging per Function

<ol type="a">
<li>A documentation page prepared for each function / modules / plugins / site-packages should have a tagging functionality. Tags are like keywords given to each page. Tags allow user to filter functions to find those that matches their needs.</li>
<li>Each page should be added with <strong>multiple tags</strong>.</li>
<li>Both developers and users should be able to create tags and add tags to any page.</li>
<li>There should be “tag administrators”, who control the tagging behaviors and also promotes the tagging. Administrators themselves should commit in active tagging.</li>
</ol>
</li>
<li>Back-links to literature

<ol type="a">
<li>In general, papers that uses image processing and analysis mention the name of the package and function that they used. This is so to say, a <strong>forward link</strong> to the tools from papers.</li>
<li>Users often wants to know examples of usages. For this reason, having <strong>back-links</strong> to literature / Pubmed abstract page / websites using the function / tool is desirable so that users could be directed to actual example usages.</li>
</ol>
</li>
<li>Comments from users

<ol type="a">
<li>A comment section should be added to each page so that any discussions / claims / questions could be viewed by other users.</li>
<li>There could be further added with the aggregation of mailing list discussions (text scrapings).</li>
<li>Access permissions (need more opinions on this issue):</li>
<li>Similar to ‘Trip advisor’ (maybe hard to actualize), each function could feature a users’ and developers’ opinion chart together with the comments, about the various implementations of a function in different software packages or about the effectiveness of a function for a certain goal/analysis. So this is similar to a point developed above, but here the question is to discuss and decide whether to include a door for users to comment on the functions and their ease-of-use. Without an interactive access by users, the Wiki would lose the ‘wiki property’ which we look forward to developing, and could quickly be seen as a restricted portal where only a handful of developers can emit judgements. Obviously the comments page could be moderated by the developer and by other users with voting (‘like it’ / ‘don’t like it’).</li>
</ol>
</li>
<li>sample datasets

<ol type="a">
<li>Links to sample datasets should be added to each page, so that user can try out the function and get a a feeling about the output to expect. As it is often difficult to know the limit of the functionality of tools, sample images will be a good reference.</li>
<li>If possible, data storage and uploading features could be added. Then the sample data could be directly uploaded by taggers for users to test, evaluate and compare.</li>
<li>When applicable ‘ground truth’ (expected) results of the function should ideally be added with each sample dataset.</li>
</ol>
</li>
</ol>


<p>A large part of the web tool should be edited manually. We propose a <strong>“taggathon”</strong> once the web tool proposed here becomes available. In this event, developers, analysts and users gather in one place and concentrate on tagging pages, back linking literature and adding documentation to each page.</p>

<h3>Meetings</h3>

<p>Meeting will be a place to collectively spread and absorb image processing and analysis activities. In terms of increasing the software packages / tools accessibility, three different types of meetings should be organized with clearly defined target groups (developers, analysts and users) and directed flow of information between these groups. As a byproduct meetings strengthen human networks that trigger individual communication to be smoother and more informal, which allows specific solutions to problems by connecting developers, analysts and users. We include teaching oriented activities, or courses, as meetings since although the format differs, we think that the functionality is common in terms of increasing the accessibility to software packages.</p>

<h4>“Show Case” meetings (Developers and Analysts)</h4>

<p>Software packages upgrade on daily basis and it is quite an effort to follow changes and new functions. An annual meeting with presentations explaining upgrades given by a developer from each software packages would be a great benefit for analysts to be updated with the latest changes. We call this a  “Show Case” meeting. In the same meeting, analysis would provide feed-backs by showing their usages, explaining merits and demerits of the software package and also to request missing functionalities. This meeting also invites prominent developers who are creating cutting edge algorithms so that the progress in the front line of image processing could also be known to developers and to analysts.</p>

<h4>Image Analysis Courses (Analysts and Users)</h4>

<p>In image analysis courses, analysts teach users on how to combine various tools to tackle practical problems, in order to narrow  the gap between software packages and user’s demands by increasing the image analysis literacy of users. The BIAS 2013 course could be a template for such courses.</p>

<p>Several outcomes will be expected from this activity. The first is that users become more fluent with image analysis, which heightens their ability to choose and assemble appropriate tools. The second is that analysts learn from other analysts how they solved some specific problems and also possibly get aware of new problems they might be expected to solve in the future. The third is that by working together the community of analysts becomes strengthened, leading to an increase in lateral communications.</p>

<p>Courses could target two different types of user group: the first group is graduate students, postdocs and research scientists. The teaching aims that they could reach a level to do basic analysis on their own. The second group is microscope facility staffs. As analysts are still missing in many places, microscope facility staffs are taking the role of analysts beside the maintenance of microscopes. For this group of people the course teaches more advanced contents and also provides and assists teaching in their own institutes (Meta-teaching).</p>

<h4>General Assembly (Developers, Analysts, Users)</h4>

<p>A general assembly is a gathering of all developers, analysts and users. During this gathering, hackathon, presentations and courses happen in parallel. This is because there are difference in interests among three different groups, but information flow between these groups could be efficiently increased by gathering at the same place. Analysts could teach users, and users could present their work and show how developers products are used, developers could report updates on their tools and libraries. In parallel the developers and analysts could also sit together in a hackathon to extend the tools. Analysts form the most capable group of people to feedback the developers with usages. More details on the merits and demerits of the general assembly could be further discussed.</p>

<ul>
<li>Developers sometimes go out from hackathon and give talks about their works. Discuss with analysts.

<ul>
<li>Hackathons are in many cases locally funded or in worst cases developers pay themselves. There should be more official support.</li>
</ul>
</li>
<li>Analysts teach and also take a part in the Hackathon (when they are not teaching). Discuss with developers on the usages.</li>
<li>Users acquire a deep knowledge on usage of tools from the developer talks. Also being taught  practical strategies from analysts. Users present their work.</li>
</ul>


<h3>Open Textbooks for BioImage Analysis</h3>

<p>A significant problem of image analysis in biology is the lack of textbooks. For image processing, there are many textbooks written by computer scientists. These textbooks are extremely valuable as they explain the users the theory behind image processing algorithms and how they are working. However, these textbooks cover only a part of the task of image analysis in biology. In addition to image processing algorithms, bioimage analysis requires knowledge on what could be measured and how to measure biological images, but this part does not exist as textbook. This aspect of bioimage analysis is supposed to fulfill in biology a role similar to that of analytical chemistry in chemistry. As it has been missing, it turned out to be the fundamental reason for this growing gap between image processing software and user’s demands.</p>

<p>To fill this gap, analysts are at work interactively to bridge biologist’s demands and the image processing world, but their work should be organized as textbooks for efficient and systematic propagation of knowledge and techniques. As a start-up BIAS 2013 course prepared original textbooks to cover the gaps and to solve the fundamental problem in the accessibility to the image processing and analysis infrastructure. The writing of these textbooks could be standardized and the textbooks published as open textbooks to provide valuable and systematic information to biologists. At the same time, the publishing of the textbooks gives a firm scientific credit to analysts, secure their activity and pave the newly appearing career path, which may further attract more people to commit in this direction.</p>

<h3>Further Actions to be considered</h3>

<p>Following is a list of actions not explained in the previous text but which will be considered in future.</p>

<ol>
<li>For interoperability, define a standard platform (could be ImageJ, Python, Icy or any other). The platform does not have to be unique but it would be good that these platforms support multiple language bindings “from scratch” (such as Python) and that the pool of functions (plugins) that is written can easily be included to any of the platforms.</li>
<li>As a roadmap, a list of algorithms “to be implemented” could be prepared based on their relevance.</li>
<li>Set up a framework for algorithm evaluation with ground truth images, these datasets could also be used as example datasets.</li>
</ol>