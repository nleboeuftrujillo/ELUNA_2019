# ELUNA_2019
<h1>Read Me</h1>
<h2>Resources</h2>

<p>I’ve relied heavily on Tabatha Farney’s advice for setting up my implementation. The following publications are particularly relevant to this project:</p>

<p>Farney, T. (2018). Using digital analytics for smart assessment. Chicago: ALA Editions.</p>

<p>Farney, T., & McHale, N. (Eds.). (2013). Web analytics strategies for information professionals: A LITA guide. Chicago: ALA TechSource.</p>

<p>Farney, T. (2016). Using google tag manager in your library. Library Technology Reports, 52(7).</p>

<p>Farney, T. (2016). Customizing google analytics for the library catalog or discovery service. Library Technology Reports, 52(7).</p>

<h2>Step-by-step</h2>

<ol>
  <li>Set up a Google Tag Manager Account</li>
  <p></p>
<li>Set up a Google Tag Manager Container</li>
<p></p>
  <p><a href="https://support.google.com/tagmanager/answer/6103696?hl=en">How to setup and install Google Tag Manager</a></p>

<p>You can set up a test account using any Google login. The account will collect no data and you can delete it when you’re finished.</p>

<p>If you would like to see how I’ve set up my container, import it from the ContainerGTMSummonexampleApril2019.json file above. <a href="https://support.google.com/tagmanager/answer/6106997?hl=en">How to import a container.</a></p> 

<li>Install the Google Tag Manager Container on Summon</li>
<p></p>
<p><a href="https://knowledge.exlibrisgroup.com/Summon/Knowledge_Articles/Can_javascript_be_added_to_Summon%3F">How to add external JavaScript in Summon</a></p>
<p>If you would like to see how I’ve set up my GTM JavaScript, see the JavascriptGTMSummonexampleApril2019.js file above.</p>

<p>The Google Tag Manager code I use is not the “standard” Google Tag Manager code. It is an altered script provided by Tabatha Farney. This alteration allows me to collect a variable called the virtualURL. I find this variable useful because it captures keyword data that otherwise I can’t see.</p> 

<li>Install Google Analytics on Google Tag Manager</li>
<p></p>
<p><a href="https://support.google.com/tagmanager/answer/6107124?hl=en">How to install Google Analytics using Google Tag Manager</a></p>

<p>If you upload my container you can see how I set mine up by looking at the “Universal Analytics - Summon-PageViews” Tag.</p>

<li>Test installation with the Google Tag Manager Debug Console.</li>
<p></p>
<p><a href="https://www.youtube.com/watch?v=vus2df3aKtY">Using the Google Tag Manager Debug Console.</a></p>
<p>If you want to see if what you created in GTM actually works you’ll need to use the Google Tag Manager Debug Console. The Debug Console lets you see what you’re collecting before you start actually collecting it.</p>

<li>Press submit to officially “launch” Google Analytics.</li>
<p></p>
<li>Test installation with Google Tag Assistant chrome extension.</li>
<p></p>
<li>Take down "old" Google Analytics account on Summon.</li>
<p></p>
<li>Start adding events.
<p>The two events I recommend starting out with is an event that tracks all of the clicks and an event that tracks when someone clicks on a facet. I've included these in the container.</p>
</ol>
