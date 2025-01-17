# Prepublishing checklist

## For all VA.gov pages

- [ ] Check all links to confirm they work and point to the intended page.
- [ ] Confirm all links contain a purpose and a target. A user will know from just the link text what the link does and where it is sending them. [Read more about making links accessible](https://www.accessibilityoz.com/2014/02/links-and-accessibility/)
- [ ] Confirm all links are 100 characters or less.
- [ ] Confirm all phone numbers are in [aria labels](https://design.va.gov/content-style-guide/dates-and-numbers#phone-numbers).
- [ ] Confirm that the heirarchy of headings is correct (H1 to H2 to H3—levels shouldn't be skipped). [Read WCAG documentation](https://www.w3.org/WAI/tutorials/page-structure/headings/)
- [ ] Check that we use [Node IDs](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/how-to-do-different-tasks/linking-with-node-ids.md) instead of urls to link to other pages within Drupal.
- [ ] Replace any sighted language ("view," "see," "look") with a word that's inclusive of our screen reader users ("check," "go to," "review").
- [ ] Avoid using other ability-focused language. ("hear back from")
- [ ] If publishing a brand-new page, [confirm the left nav and url are set up correctly](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/how-to-do-different-tasks/adding-left-nav-and-url.md). (If the page is a child page, the section needs to be the same as the parent page in order for the left nav to show.)
- [ ] Make sure all apostrophes and quotation marks are curly not straight.
- [ ] Confirm that there are no updates in draft by other content authors that aren't ready to be published. Check the revision log and then confirm with the content author who made the previous edits that the page is ready to publish.

## For Resources and Support articles

- [ ] Confirm H2s, H3s, and H4s are within the 70-character limit.
- [ ] Confirm related links have been added to the file and make sense for the topic of the page (i.e., they’re actually related to the article—rather than “something you may also be interested in”—and there isn’t an obvious one that’s missing).
- [ ] Determine if this new article should be added as a related link on any live articles. 
- [ ] Make sure the wording for the action link (call to action link text) matches other pages that use the same link.
- [ ] If linking off of VA.gov, make sure the words in the label or button indicate to the user that they're leaving VA.gov.
- [ ] Check that any screenshots contain alt text that contain context.
- [ ] **For multiple FAQs:** First publish each single Q&A and then publish the multiple FAQ.

**Also confirm these components are checked in the Drupal file:**</br>
- [ ] The correct primary article category and additional article categories. 
- [ ] The correct benefit hub contacts. 
- [ ] The appropriate audience and topic tags. 
- [ ] "Repeat CTA buttons" box if it's a long article. This will display the action link at both the top and bottom of the page.
- [ ] **For a single Q&A:** "Enable standalone Resources and support page for this Q&A."

# Post-publishing R&S checklist

- [ ] Add the article to the R&S landing page in the correct hub. If there are already more than 5 articles in that hub, you don't need to add it unless you want it to replace another article already on the page.
- [ ] If the article is the sixth one in a hub to be published, add the "Go to all articles" link at the bottom of the hub section on the landing page.
- [ ] Add the new article and its action link wording to our [Github file of button labels](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/resources-and-support/rs-cta-button-audit.md).
- [ ] Add the new article to our [Github file of R&S articles](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/resources-and-support/resources-and-support-article-list.md).
- [ ] Notify the Content Center Support team in their Slack channel (#vsp-contact-center-support) that we've published a new article. Provide the link and a few details about the article. It may be helpful to them for either communicating with Veterans or researching questions themselves. 
