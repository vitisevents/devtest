---
layout: "default"
title: Speakers
metatitle: Speakers
group: "navigation"
weight: 2
image: banners/speakers.png
---
<div class="page-title speakers">
    <div class="wrapper">
      <h1 align="center">Call for papers is now open!</h1>
    </div>
</div>
<div class="wrapper">
    <div class="row">
        <!-- <div class="container">
            <div class="col span12">
                <ul class="speakers">
                    <h2>Master of Ceremonies<h2>
                    {% for day in site.data.2020.speakers %}
                        {% for slot in day.slots %}
                            {% if slot.slottype == 'mc' %}
                                {% for speaker in slot.tracks %}
                                {% if speaker.track.speakers %}
                                    {% for sp in speaker.track.speakers %}
                                        {% include post-components/speaker.html speaker=sp %}
                                    {% endfor %}
                                {% else %}
                                    {% include post-components/speaker.html speaker=speaker.track %}
                                {% endif %}
                                {% endfor %}
                            {% endif %}
                        {% endfor %}
                    {% endfor %}
                    <h2>Keynote Speakers<h2>
                    {% for day in site.data.2020.speakers %}
                        {% for slot in day.slots %}
                            {% if slot.slottype == 'keynote' %}
                                {% for speaker in slot.tracks %}
                                {% if speaker.track.speakers %}
                                    {% for sp in speaker.track.speakers %}
                                        {% include post-components/speaker.html speaker=sp %}
                                    {% endfor %}
                                {% else %}
                                    {% include post-components/speaker.html speaker=speaker.track %}
                                {% endif %}
                                {% endfor %}
                            {% endif %}
                        {% endfor %}
                    {% endfor %}
                    <h2>Workshop Speakers<h2>
                    {% for day in site.data.2020.speakers %}
                        {% for slot in day.slots %}
                            {% if slot.slottype == 'workshop' %}
                                {% for speaker in slot.tracks %}
                                {% if speaker.track.speakers %}
                                    {% for sp in speaker.track.speakers %}
                                        {% include post-components/speaker.html speaker=sp %}
                                    {% endfor %}
                                {% else %}
                                    {% include post-components/speaker.html speaker=speaker.track %}
                                {% endif %}
                                {% endfor %}
                            {% endif %}
                        {% endfor %}
                    {% endfor %}
                    <br>
                    <h2>Breakout Session Speakers<h2>
                    {% for day in site.data.2020.speakers %}
                        {% for slot in day.slots %}
                            {% if slot.slottype != 'mc' and slot.slottype != 'keynote' and slot.slottype != 'workshop' %}
                                {% for speaker in slot.tracks %}
                                    {% if speaker.track.speakers %}
                                        {% for sp in speaker.track.speakers %}
                                            {% include post-components/speaker.html speaker=sp %}
                                        {% endfor %}
                                    {% else %}
                                        {% include post-components/speaker.html speaker=speaker.track %}
                                    {% endif %}
                                {% endfor %}
                            {% endif %}
                        {% endfor %}
                    {% endfor %}
                </ul>
            </div>
        </div>
    </div>
</div> --> 
           <p><strong><h2>Our Call for Papers opens 4th September 2019, and closes 15th October 2019.</h2></strong></p>

      <p>PHP UK Conference is focused on education and discussion of the PHP programming language. We aim to attract the best speakers, contributors, and educators from around the world in hopes of providing the community with the best resources on the PHP programming language every year.</p>

      <p>We are looking for speakers and instructors to give talks and hands-on classroom sessions. We are seeking talks covering mainstream, advanced, niche or non-technical topics aimed at a multitude of skill levels.</p>

    <h2>About</h2>
    <p>PHP UK seeks to deliver ‘wow’ talks that are fresh and inspiring about cutting edge topics or new perspectives on common problems. The audience will be from all backgrounds varying in skill level from beginner to intermediate to advanced, so talks varying widely in topic and skill levels are required. Most of all we want speakers who have a deep knowledge about the topics they are proposing and can’t wait to share that knowledge with a whole group of of eager listeners. Tell us what you’re most passionate about and why we should be passionate about it as well.</p>

    <h2>Talk Types</h2>
    <p>We are looking for 3 different types of talks for the event:</p>

    <h3>Workshops</h3>
    <ul>
        <li>Hand on technical training</li>
        <li>Classroom style</li>
        <li>Technical, in depth tutorial content on a specific topic</li>
        <li>Full day (8 hours, 6 hours actual training time)</li>
        <li>Not video recorded or distributed online</li>
    </ul>

    <h3>Keynotes</h3>
    <ul>
        <li>Opening and closing sessions each day of the conference</li>
        <li>Motivational, big ideas, inspirational, and community related topics</li>
        <li>Full conference audience</li>
        <li>30 minutes length</li>
        <li>No Q&A</li>
        <li>4 keynote sessions will be selected</li>
    </ul>

    <h3>Talk Sessions</h3>
    <ul>
        <li>Breakout sessions throughout the conference</li>
        <li>Technical, educational, research, new technology, case studies</li>
        <li>Partial conference audience (split across 3 tracks)</li>
        <li>60 minutes length</li>
        <li>Q&A at speaker’s discretion (within 45m limit)</li>
        <li>16 talk sessions will be selected</li>
        <li>Sessions will be recorded and made available online after the conference</li>
    </ul>

    <h3>Tutorials</h3>
    <ul>
        <li>Classroom style</li>
        <li>Technical, in depth tutorial content on a specific topic</li>
        <li>2 hours length</li>
        <li>Suggested 1 hour slide content, 1 hour hands-on exercises</li>
        <li>Partial conference audience (split across 3 tracks)</li>
        <li>Not video recorded or distributed online</li>
        <li>8 tutorial sessions will be selected</li>
    </ul>

    <p>Both keynotes and talk sessions are video recorded and distributed for free along with your slides on our YouTube channel.</p>

    <h2>Speakers</h2>
    <p>We believe diversity of speakers and topics makes our event better. We welcome speakers of all programming languages, experience levels and backgrounds. We welcome speakers of any gender, sexual orientation, disability, physical appearance, race, or religion. We welcome new speakers and experienced speakers alike.</p>
    <h2>Speaker's Package</h2>
    <p>We are very pleased to be able to offer the following benefits package to all our speakers:</p>
    <ul>
        <li>Entry to the conference and all the social events</li>
        <li>Travel expenses paid in full</li>
        <li>Three nights hotel so you can attend the whole conference</li>
        <li>Invitation to the speaker’s dinner</li>
    </ul>

        <div class="callout -green">
            <a class="button -inverse -square right" href="https://www.papercall.io/phpuk2020" target="_blank">Submit here</a>
            <h4>Submit a paper</h4>
            <p>If you'd like to submit a paper for consideration to speak at the conference, learn more and submit your details here.</p>
    </div>
</div>