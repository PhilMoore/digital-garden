
# Holgro - Events Page troubleshooting

09/06/21

Events page showing up blank despite having events created

should be auto created & populated through Events calendar plugin

info:

[Locating Your Calendar | Knowledgebase | The Events Calendar](https://theeventscalendar.com/knowledgebase/k/finding-your-calendar-on-the-front-end/)

[Finding Links for Specific Event Views | Knowledgebase | The Events Calendar](https://theeventscalendar.com/knowledgebase/k/linking-to-specific-event-views/)

1.  tried accessing the different view links, blank pages.

[The Events Calendar Shortcode & Block | Knowledgebase | The Events Calendar](https://theeventscalendar.com/knowledgebase/k/the-events-calendar-shortcode-block/)

1.  tried making a page with the [tribe_events] shortcode,

with the tribe events stying template active in events > settings > display

does not work

1.  tried switching template styles & views, makes no difference.

No customise section for events calendar plugin.. when there should be.

15/06/21

it was this custom CSS to hide the calendar page….

/ _Events - Hidden until we have some_ /

.post-type-archive-tribe_events .page-content {

display:none;

}

# check this for customizing:

99% sure the style has been customized and need to know how

[WordPress Customizer for Calendar Views (V2) | Knowledgebase | The Events Calendar](https://theeventscalendar.com/knowledgebase/k/wordpress-customizer-2/)

[Basic Template Settings | Knowledgebase | The Events Calendar](https://theeventscalendar.com/knowledgebase/k/basic-template-settings/)