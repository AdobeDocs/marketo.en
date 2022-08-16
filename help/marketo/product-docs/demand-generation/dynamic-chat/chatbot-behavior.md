---
description: Chatbot Behavior - Marketo Docs - Product Documentation
title: Chatbot Behavior
hide: yes
hidefromtoc: yes
---
# Chatbot Behavior {#chatbot-behavior}

The following are different possible scenarios outling the Chatbot's expected behavior the visitor in each one.

<table>
  <tbody>
    <tr>
      <th>Abbreviation</th>
      <th>Details</th>
    </tr>
    <tr>
      <td>D1, D2, D3, etc.</td>
      <td>Represents multiple dialogues where D1 is dialogue one</td>
    </tr>
    <tr>
      <td>P1, P2, P3, etc.</td>
      <td>Represents dialogue priorities where P1 is the highest priority</td>
    </tr>
    <tr>
      <td>WP1, WP2, WP3, etc.</td>
      <td>Represents multiple web pages where WP1 is the first web page</td>
    </tr>
    <tr>
      <td>V1, V2, V3, etc.</td>
      <td>Represents multiple web page visitors where V1 is visitor one</td>
    </tr>
   </tbody>
</table>

## Scenarios {#scenarios}

<table>
  <tr>
      <th>Scenario</th>
      <th>Expected Chatbot Behaviour</th>
      <th>Backend action</th>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 </p>
      </td>
      <td>The trigger count for D1 should be increased by 1</td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1</p>
        <p>After refresh, D1 should be resolved again</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>After refresh, no change to D1 trigger or engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond</p>
      </td>
      <td>D1 should be resolved to V1</td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>No change to D1 engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and provides the first response</p>
      </td>
      <td>D1 should be resolved to V1</td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>The engagement count for D1 should be increased by 1</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and provides the first response</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1</p>
        <p>After refresh, D1 should be continued</p>
      </td>
      <td>
        <p>The trigger count and engagement count for D1 should be increased by 1</p>
        <p>After refresh, no change to any count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1, engages with the chatbot, and completes D1</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1</p>
        <p>After refresh, no dialogue or next dialogue should be resolved for V1</p>
      </td>
      <td>
        <p>The trigger count, engagement count, and completed count for D1 should be increased by 1</p>
        <p>After refresh, no dialogue or next dialogue should be resolved</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only, WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond </p>
        <p>V1 visits WP2</p>
      </td>
      <td>
        <p>Page visit WP1, D1 should be resolved to V1</p>
        <p>Page visit WP2, D1 should be resolved to V2</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>In WP2, no change to D1 trigger count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only, WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and engaged</p>
        <p>V1 visits WP2</p>
      </td>
      <td>
        <p>Page visit WP1, D1 should be resolved to V1</p>
        <p>Page visit WP2, D1 should be resolved to V1</p>
      </td>
      <td>
        <p>The trigger count and engagement count for D1 should be increased by 1</p>
        <p>In WP2, no change to any count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>D2 targeted for only WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and provides the first response</p>
        <p>V1 visits WP2</p>
      </td>
      <td>
        <p>D1 should be resolved on WP1</p>
        <p>D1 should continue to V1 on WP2</p>
      </td>
      <td>
        <p>The trigger count and engagement count for D1 should be increased by 1</p>
        <p>No change to D2 trigger or engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>D2 targeted for only WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond </p>
        <p>V1 visits WP2</p>
      </td>
      <td>D1 should be resolved on WP1<br/>
      D2 should be resolved on WP2</td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>The trigger count for D2 should be increased by 1</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>D2 targeted for only WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and completes D1</p>
        <p>V1 visits WP2</p>
      </td>
      <td>D1 should be resolved on WP1 and on post-completion<br/>D2 should be resolved on WP2</td>
      <td>
        <p>The trigger count, engagement count, and completed count for D1 should be increased by 1</p>
        <p>The trigger count for D2 should be increased by 1</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>D2 targeted for only WP2</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and completes D1</p>
        <p>V1 visits WP2</p>
        <p>V1 clicks on D2 provides the first response </p>
      </td>
      <td>D1 should be resolved on WP1 and on post-completion<br/>D2 should be resolved on WP2</td>
      <td>
        <p>The trigger count, engagement count, and completed count for D1 should be increased by 1</p>
        <p>The trigger and engagement count for D2 should be increased by 1</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond</p>
        <p>D1 is unpublished</p>
      </td>
      <td>D1 should be resolved to V1</td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>No change to the D1 engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond</p>
        <p>D1 is unpublished</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 for the first time</p>
        <p>After refresh, no dialogue should be resolved</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>No change to the D1 engagement count</p>
        <p>After refresh, no change to the D1 trigger or engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 engaged with D1 </p>
        <p>D1 is unpublished</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1</p>
        <p>After refresh, D1 should be continued</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>D1 engagement count should be increased by 1</p>
        <p>After refresh, as D1 will be continued no further change to trigger or engagement count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond</p>
        <p>D1 is published with new changes</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 for the first time</p>
        <p>After refresh, dialogue with new changes should be resolved</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>After refresh, as D1 with new changes but no further change to trigger count</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 only</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 provides the first response</p>
        <p>D1 is published with new changes</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 for the first time</p>
        <p>After refresh, dialogue with old changes should continue</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>The engagement count for D1 should be increased by 1 </p>
        <p>After refresh, as the old D1 will appear so no change to trigger count</p>
      </td>
    </tr>
    <tr>
     <td>
        <p>D1 targeted for WP1 with 1 priority</p>
        <p>D2 targeted for WP1 with 2 priority</p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 but did not respond</p>
        <p>D1 is unpublished</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 for the first time</p>
        <p>After refresh, D2 should be resolved to V1</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>After refresh, the trigger count for D2 should be increased by 1</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 with 1 priority</p>
        <p>D2 targeted for WP1 with 2 priority </p>
        <p>V1 visits WP1 for the first time</p>
        <p>V1 clicks on D1 and completes D1</p>
        <p>V1 refreshes WP1 and see D2<br/>V1 clicks on D2 and completes D2</p>
        <p>Marketer made changes to D1 and republished</p>
        <p>V1 refreshes WP1</p>
      </td>
      <td>
        <p>D1 should be resolved to V1 for the first time</p>
        <p>After refresh, D2 should be resolved to V1</p>
        <p>After completing D1 and D2, irrespective of what changes or re-published D1, D2 should not be shown again to V1</p>
      </td>
      <td>
        <p>The trigger count, engagement count, and completed count for D1 should be increased by 1</p>
        <p>Refresh after D2 completes, no action to be taken</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 with "Time on Site" trigger of 30 seconds</p>
        <p>V1 visits WP1</p>
      </td>
      <td>
        <p>D1 should be resolved but will not be triggered to V1</p>
        <p>After 30 seconds, D1 should be shown/triggered to V1</p>
      </td>
      <td>The trigger count for D1 should be increased by 1 only after 30+ seconds spent on webpage</td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1, WP2 with "Time on page" trigger of 30 seconds</p>
        <p>V1 visits WP1, WP2</p>
      </td>
      <td>
        <p>D1 should be resolved but will not be triggered to V1</p>
        <p>After 30 seconds, D1 should be shown/triggered to V1</p>
      </td>
      <td>The trigger count for D1 should be increased by 1 only after 30+ seconds spent on webpage</td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 with "scroll percentage" trigger of 50</p>
        <p>V1 visits WP1</p>
      </td>
      <td>
        <p>D1 should be resolved but will not be triggered to V1</p>
        <p>After 50% scroll, D1 should be shown/triggered to V1</p>
      </td>
      <td>The trigger count for D1 should be increased by 1 only after 50% scrolled</td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 with 1 priority and event "Time on page" trigger of 30 seconds</p>
        <p>D2 targeted for WP1 with 2 priority and event "page scroll percentage" of 50</p>
        <p>V1 visits WP1, after 10 seconds V1 visits WP2, V1 visits WP1</p>
      </td>
      <td>
        <p>On WP1, D1 should be resolved but will not be triggered to V1</p>
        <p>On WP2, D2 should be resolved but will not be triggered to V1</p>
        <p>On WP1, D1 should be resolved and after 20 seconds D1 should be triggered to V1</p>
      </td>
      <td>The trigger count for D1 should be increased by 1 only after 30 seconds</td>
    </tr>
    <tr>
      <td>
        <p>D1 targeted for WP1 with "Time on Site" trigger of 1 minute</p>
        <p>V1 visits WP1 for 1 minute and is shown D1 but does not engage</p>
        <p>V1 closes WP1 and comes back to WP1 2 days later</p>
      </td>
      <td>
        <p>D1 should automatically be shown to V1 as they have already met the trigger criteria during the previous session</p>
        <p>The same logic should apply to "Time on Page" and "page scroll percentage"</p>
      </td>
      <td>
        <p>The trigger count for D1 should be increased by 1</p>
        <p>After return, no action to be taken</p>
      </td>
    </tr>
  </tbody>
</table>
