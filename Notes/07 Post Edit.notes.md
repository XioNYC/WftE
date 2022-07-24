# Post-Production

Output for the editor to use.

## Editing

### File Formats
* 16-bit
* Monaural
* &lt;2<sup>31</sup>-1 bytes
	* CD Quality WAVE (stereo)<br />&le;03:22:53 (12,173 sec)
	* DAT Quality WAVE (stereo)<br />&le;03:06:24 (11,184 sec)

### Workflow
* Check that you have all the components of the audiobook
* Label all the logical sections.<br />Refer to the table of contents.

	* Label page breaks

* Make sure you have the preliminary header and concluding materials (metadata).

* Finesse the audio quality *last*.

	The point of perfecting audio is lost if the audiobook is incomplete.

	Check your guidelines and specifications for peaks, signal-to-noise measurements, and pausing/pacing.

### Transmission

* FLAC
* ``.tar.xz``-ed WAVs

* **Do not transmit MP3 to editors**

	Lossy codecs is lost quality.

* **Do not transmit Ogg to editors**

	You can't guarantee they'll be able to read it.

* **Tarball Audacity Projects**

	You'd be amazed how many people fail to send the audio - just the index file (``.aup``)

* Clean 8.3 Filenames<br />`([A-Z0-9]{1,8})(\.{0,1}[A-Z0-9]{1,3})`

	<blockquote><center><b>x&#x131;o&rsquo;s <span style="font-variant: small-caps;">mantra</span></b><br /><center>Never underestimate the ubiquity of and reliance upon irreplaceable and unupgradeable well past end-of-life equipment fulfilling mission-ciritical production roles.</center></blockquote>