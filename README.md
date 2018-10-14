Getting started with OSS.
=========================
```
<section>
    <h2>Getting Started With Open Source Contributions</h2>
    <h4>A good career move.</h4>
    <br>
        <small>Created by
            <a href="https://github.com/chtompki">
                Rob Tompkins (chtompki)</a></small><br/>
        <small>Presentation Address: <a href="https://chtompki.github.io/getting-started-with-oss/#/">
            https://chtompki.github.io/getting-started-with-oss/#/</a></small>
    </p>

</section>

<section>
<h2>What is <a href="http://commons.apache.org">apache commons</a>?</h2>
<ul>
    <li class="fragment">Common location for sharing code for Apache projects.</li>
    <li class="fragment">Was jakarta commons (jakarta being the apache java project).</li>
    <li class="fragment"><strong>Current mission:</strong> Provide a place for other ASF projects to
        come together, collaborate and share
        common code.</li>
</ul>
</section>

<section>
    <h2>Does anyone not know what an open source project is?</h2>
    <p class="fragment">
        <strong>Def'n.</strong> In general, open source refers to any program whose source code
        is made available for use or modification as users or other developers see fit.
    </p>
</section>

<section>
    <h2>What are the benefits of open source software?</h2>
    <ul>
        <li class="fragment">Accommodation of a type of standardization.</li>
        <li class="fragment">More eyes = fewer bugs.</li>
        <li class="fragment">Long term support.</li>
    </ul>
</section>

<section>
    <h2>[Benedikt] Ritter's Law</h2>
    <p class="fragment">
        Everything that is not part of our domain/business logic or the crazy legacy
        systems we need to integrate has already been developed by somebody
        much smarter than us....
    </p>
    <p class="fragment">
        Don't re-invent the wheel!
    </p>
</section>

<section>
    <h2>Why did I get involved?</h2>
    <ol>
        <li class="fragment">To keep my mathematics sharp(er).</li>
        <li class="fragment">Career advancement?</li>
        <li class="fragment">You're not constrained by timelines...you can get it right.</li>
    </ol>
</section>

<section>
    <section>
        <h2>Ok, so what did you do to get involved?</h2>
        <ol>
            <li class="fragment">Pick a subject that you're passionate about.</li>
            <li class="fragment">If it's on git check the stats page to see who
                frequent committers are. For example consider
                <a href="https://github.com/apache/commons-lang/graphs/contributors">this github
                    contributors page</a></li>
        </ol>
    </section>
    <section>
        <p>
            <img src="images/commons-lang-contributors.png" style="max-width: 600px;"/>
        </p>
    </section>
</section>

<section>
    <section>
        <h2>How to ask people what to work on?</h2>
        <ol>
            <li class="fragment">Find emails or mailing lists.</li>
            <ul>
                <li class="fragment">For example consider this link from the <code>[lang]</code>
                    <a href="https://github.com/apache/commons-lang/blob/master/README.md">README.md</a>:
                    <a href="https://commons.apache.org/mail-lists.html">user mailing list</a>.
                </li>
            </ul>
            <li class="fragment">Email someone directly.</li>
        </ol>
    </section>
    <section>
        <p>
            <img src="images/mail-lists.png" style="max-width: 800px;"/>
        </p>
    </section>
</section>

<section>
    <h2>How do I figure out what to work on?</h2>
    <ul>
        <li class="fragment">Tests, tests, and more tests.</li>
        <ul>
            <li class="fragment">No one has 100% coverage, there's always room for test improvements.</li>
        </ul>
        <li class="fragment">Find a ticket. My first major contribution other than tests was
            <a href="https://issues.apache.org/jira/browse/LANG-1252">LANG-1252</a>.
            <ul>
                <li class="fragment">After 4 months of writing tests.</li>
            </ul>
        </li>
    </ul>
</section>

<section>
    <section>
        <h2>Becoming familiar with the community</h2>
        <ul>
            <li class="fragment">Read the documentation on all project aspects.</li>
            <li class="fragment">
                Don't be afraid to weigh in on mailing list discussions, but do be polite
                <ul>
                    <li class="fragment">Try to stick to +/- 0 votes</li>
                </ul>
            </li>
        </ul>
    </section>
    <section>
        <h2>On ASF Style voting.</h2>
        <ul>
            <li class="fragment"><strong>+1</strong> - Yes.</li>
            <li class="fragment"><strong>+0</strong> - I'm ok with this, but I think it has issues.</li>
            <li class="fragment"><strong>-0</strong> - I'm ok with this, but I'd like to express a dissenting
                opinion because I see potentially veto-worthy issues.
            </li>
            <li class="fragment">
                <string>-1</string>
                - Veto.
            </li>
        </ul>
        <p class="fragment">
            This is used to gauge consensus, not really "majority rule." In fact with releases,
            generally, any -1 vote cancels the release.
        </p>
    </section>
</section>

<section>
    <h2>Regarding privileges</h2>
    <h4>(commit, voting, establishing votes, ect.)</h4>
    <section>
        <p class="fragment">
            <br/>
            Clearly this is all community dependent, but commons (and Apache generally) has the following:
        </p>
        <ul>
            <li class="fragment"><strong>user</strong> - anyone consuming the software.</li>
            <li class="fragment"><strong>contributor</strong> - anyone who has made a contribution.</li>
            <li class="fragment">
                <strong>committer</strong> - anyone who can commit directly
                <ul>
                    <li class="fragment">Can make any changes to site or component.</li>
                    <li class="fragment">Can present votes.</li>
                    <li class="fragment">Can perform releases (according to the process).</li>
                </ul>
            </li>
        </ul>
    </section>
    <section>
        <ul>
            <li class="fragment"><strong>committee member</strong> - has voting privileges
                <ul>
                    <li class="fragment">Voting privileges particularly matter with releases, new components,
                        and such.
                    </li>
                    <li class="fragment">Proposing new committers.</li>
                </ul>
            </li>
            <li class="fragment"><strong>committee chair</strong> - prepares the quarterly reports......ugh.</li>
        </ul>
    </section>
</section>

<section>
    <h2>After I got commit rights.</h2>
    <ul>
        <li class="fragment">Asked Benedikt, and Gary what they thought I should do.</li>
        <li class="fragment"><code>[text]</code>, a sandbox component, needed to be taken out.</li>
        <li class="fragment">Read up on release process:
            <a href="http://commons.apache.org/releases/index.html">Releasing Components</a>.
            <ul>
                <li class="fragment">Beta release.</li>
                <li class="fragment">Two dot releases.</li>
            </ul>
        </li>
    </ul>
</section>

<section>
    <h2>Other activities.</h2>
    <ul>
        <li class="fragment">Spoke on <code>[text]</code> at ApacheCon:
            <a href="https://www.youtube.com/watch?v=rqBJHpQ5yvo">video of presentation.</a></li>
        <li class="fragment">Helped release <code>[fileupload]</code> for security fixes.</li>
        <li class="fragment">Helped to validate releases (non-binding).</li>
        <li class="fragment">Voted into PMC in June 2017.</li>
        <li class="fragment">Fixed
            <a href="https://www.cvedetails.com/cve/CVE-2017-12621/">CVE-2017-12621</a></li>
        <li class="fragment">Created commons-release-plugin</li>
    </ul>
</section>

<section>
    <h1>Questions?</h1>
    <h4 class="fragment">Appetite for exploring commons?</h4>
</section>
```

Then Talk about the examples...(As of 5/19/2017, the talk is only 30 mins....I need more examples).
