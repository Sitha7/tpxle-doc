# Key smart badge commands
This table gives you quick access to the smart badge commands. For more information, see [Abeeway Trackers Reference Guide](/D-Reference/DocLibrary_R/#abeeway-trackers) and [LED patterns](/D-Reference/DocLibrary_R/#abeeway-trackers).
::: warning Important
 * Pressing the button **shortly** lasts **less than one second**.
 * Pressing the button **lengthily** lasts **more than five seconds**.
:::
<html>
<table cellspacing="21">
    <colgroup>
        <col/>
        <col/>
    </colgroup>
    <thead>
    <tr>
        <th><strong>How to...</strong>
        </th>
        <th>
            <p>Action</p>
        </th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td><strong>Switch on</strong>
        </td>
        <td><strong>Press</strong> the button <strong>once lengthily</strong> (more than five seconds) <strong>until you
            heard a melody</strong>.<p>-&gt; The smart badge starts in motion tracking mode in standard
            configuration.</p>
            <p>The sequence to follow is the same for the micro tracker and the smart badge:</p>
            <p>
                <iframe class="youtube-player_0" src="https://www.youtube.com/embed/T9dfVbptpsM?" frameborder="0"
                        allowfullscreen="1" width="300px" height="150px"></iframe>
            </p>
        </td>
    </tr>
    <tr>
        <td><strong>Switch off</strong>
        </td>
        <td><strong>Press</strong> the button <strong>once lengthily</strong> (more than five seconds) <strong>until you
            heard a melody</strong>.<p>-&gt; If the smart badge in on, it switches off.</p>
            <p>The sequence to follow is the same for the micro tracker and the smart badge:</p>
            <p>
                <iframe class="youtube-player_0" src="https://www.youtube.com/embed/gNtn3KRglrU?" frameborder="0"
                        allowfullscreen="1" width="300px" height="150px"></iframe>
            </p>
        </td>
    </tr>
    <tr>
        <td><strong>Check On/Off status</strong>
        </td>
        <td class="TableStyle-Alternate-Row-Color-BodyD-Column1-Body1"><strong>Press</strong> the button <strong>once
            shortly</strong> (less than one second).<p>-&gt; If the smart badge is on, the blue led flashes.</p>
            <p>The sequence to follow is the same for the micro tracker and the smart badge:</p>
            <p>
                <iframe class="youtube-player_0" src="https://www.youtube.com/embed/0b3yLGs_4Gw?" frameborder="0"
                        allowfullscreen="1" width="300px" height="150px"></iframe>
            </p>
        </td>
    </tr>
    <tr>
        <td><strong>Trigger SOS mode/Stop SOS mode</strong>
        </td>
        <td><strong>Press</strong> the button <strong>twice shortly</strong> (less than one second).
            <div class="custom-block tip">
                <p class="custom-block-title">Note</p>
                <p>When this feature is activated (<span class="CodeInline">config_flags</span>
                    must be set to <span class="CodeInline">bit 2=1</span>), the behavior is the following:</p>
                <ul>
                    <li>
                        The tracker sends positions continuously at a fixed period of 120 seconds.
                    </li>
                    <li>
                        The tracker’s blue led is blinking slowly.
                    </li>
                    <li>
                        To stop SOS mode, double-click the button again.
                    </li>
                    <li>
                        For MCU FW: 2.0 and below, SoS is triggered by double click. For MCU FW: 2.1/2.2, SoS is triggered by triple click. For MCU FW: 2.3 and above, SoS button sequence is configurable but it is triggered by triple click (by default)
                    </li>
                    <p>
                        <iframe class="youtube-player_0" src="https://www.youtube.com/embed/HgsMfytTue4?" frameborder="0"
                                allowfullscreen="1" width="300px" height="150px"></iframe>
                    </p>
                </ul>
            </div>
        </td>
    </tr>
    <tr>
        <td><strong>Trigger a position alert</strong>
        </td>
        <td><strong>Press</strong> the button <strong>twice shortly</strong> (less than one second).
            <div class="custom-block tip">
                <p class="custom-block-title">Note</p>
                <p> When this feature is activated (<span class="CodeInline">config_flags</span>
                    must be set to <span class="CodeInline">bit 2=0</span>), the behavior is the following:</p>
                <ul>
                    <li>
                        To trigger position alert, double-click the button.
                    </li>
                    <li>
                        The tracker sends one time position.
                    </li>
                    <li>
                        For MCU FW: 2.0 and below, position alert is triggered by double click. For MCU FW: 2.1/2.2, position alert is triggered by triple click. For MCU FW: 2.3 and above, position alert sequence is configurable but it is triggered by triple click (by default)
                    </li>
                    <p>The sequence to follow is the same for the micro tracker and the smart badge:</p>
                    <p>
                        <iframe class="youtube-player_0" src="https://www.youtube.com/embed/7BAg7XF2jyk?" frameborder="0"
                                allowfullscreen="1" width="300px" height="150px"></iframe>
                    </p>
                </ul>
            </div>
        </td>
    </tr>
    <tr>
        <td><strong>Re-do a join request</strong>
        </td>
        <td>Apply <a href="../../C-Procedure-Topics/ReDoJoinRequestSB_T/" class="MCXref xref">Re-doing a smart badge
            join request</a>.
        </td>
    </tr>
    </tbody>
</table>
</html>
