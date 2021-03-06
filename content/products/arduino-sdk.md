---
title: "TelemetryJet Arduino SDK"
hideSignup: true
---
<div class="sectionWrapper overflowHiddenSection">
    <section class="landingSection">
        <div class="sectionBackground">
		</div>
		<div class="sectionForeground">
			<div class="row top-xs between-xs">
				<div class="col-xs-12 col-md-6" style="z-index: 1;">
                    <h1>A lightweight, flexible library for communicating with microcontrollers</h1>
					<div class="landingPageOutlineHeading">
						Bidirectional communication
					</div>
                    <p>
					Establish a robust bidirectional link to your embedded device with minimal code. Data points are automatically transmitted and received over a serial connection using an efficient and reliable encoding.
                    </p>
					<div class="landingPageOutlineHeading">
						Strong typing
					</div>
                    <p>
                    Transmit numerical data points with fine-grained control over the resolution of your data, for communication over limited-bandwidth connections.
                    </p>
					<div class="landingPageOutlineHeading">
						Data Caching and Expiration
					</div>
                    <p>
					Filter incoming data, so your microcontroller only stores values you’ve selected. Data you’ve subscribed to caches locally on your device. 
					</p>
					<div class="landingPageOutlineHeading">
						Easy integration with any software
					</div>
                    <p>
                    Easily parse messages in any program using <a href="https://msgpack.org/index.html">MessagePack's language bindings</a>, or use the TelemetryJet CLI to stream data into other data sources without code.
                    </p>
                </div>
				<div class="col-xs-0 col-sm-0 col-md-0 col-lg-6">
					<img id="arduinoSdkLargeImage" src="/img/arduino-sdk-robot.png" />
				</div>
				<div class="col-xs-0 col-sm-0 col-md-6 col-lg-0">
					<img id="arduinoSdkMediumImage" src="/img/arduino-sdk-robot.png" />
				</div>
				<div class="col-xs-12 col-sm-12 col-md-0 col-lg-0">
					<img id="arduinoSdkSmallImage" src="/img/arduino-sdk-robot.png" />
				</div>
			</div>
			<div class="clearfix"></div>
		</div>
    </section>
</div>
<div class="sectionWrapper landingSectionHighlight">
    <section class="landingSection">
        <div class="sectionBackground">
		</div>
		<div class="sectionForeground">
			<div class="row top-xs between-xs">
				<div class="col-xs-12 col-md-6">
					<br/>
					<div class="landingPageOutlineHeading">
						Extensive Documentation
					</div>
					<p>
					The TelemetryJet <a href="https://docs.telemetryjet.com/arduino_sdk/">documentation site</a> contains detailed guides and an API reference for the SDK.
					</p>
					<div class="landingPageOutlineHeading">
						Detailed Examples
					</div>
					<p>
					The Arduino library includes detailed examples. Learn to read and write data points,
					configure a telemetry connection, and send typed data.
					</p>
				</div>
				<div class="col-xs-12 col-md-6 col-lg-6">
					<pre class="bp3-code" style="overflow: auto">
#include &lt;TelemetryJet.h&gt;<br/>
// Initialize the telemetry instance and a data dimension
TelemetryJet telemetry(&Serial, 100);
Dimension sensorValue = telemetry.createDimension(1);<br/>
void setup() {
    Serial.begin(115200);
}<br/>
void loop() {
    // Update the sensor value from analog input
    sensorValue1.setUInt16(analogRead(A0));
    telemetry.update();
}</pre>
				</div>
			</div>
	</section>
</div>
<div class="sectionWrapper landingSectionHighlight overflowHiddenSection secondaryHero bp3-dark">
    <section class="landingSection">
        <div class="sectionBackground">
		</div>
		<div class="sectionForeground">
			<div class="row top-xs between-xs">
				<div class="col-xs-12">
					<h1>Get Started Now</h1>
				</div>
				<div class="col-xs-12 col-md-6">
					<div class="landingPageOutlineHeading">
						Install the Library
					</div>
					<p>
					Install the TelemetryJet Arduino SDK via the Arduino Library Manager. Just search for "TelemetryJet".
					</p>
				</div>
				<div class="col-xs-12 col-md-6">
					<div class="landingPageOutlineHeading">
						Learn
					</div>
					<p>
					The TelemetryJet Arduino SDK comes with detailed documentation, API references, and examples. The documentation site will guide you through getting started with the SDK.<br /><br /><a href="https://docs.telemetryjet.com/arduino_sdk/" class="bp3-button bp3-large bp3-primary bp3-intent-primary bp3-fill bp3-icon-arrow-right">Read the Docs</span></a>
					</p>
				</div>
			</div>
	</section>
</div>
<div class="sectionWrapper">
    <section class="landingSection">
        <div class="sectionBackground">
		</div>
		<div class="sectionForeground">
			<div class="row middle-xs between-xs">
				<div class="col-xs-12 col-md-6">
					<h1>100% Free and Open Source</h1>
					<p>
					The TelemetryJet Arduino SDK and TelemetryJet CLI are free and open-source under the MIT license. You can use and modify either project for any purpose.<br />
				</div>
				<div class="col-xs-12 col-md-6 col-lg-6">
					<div class="landingPageOutlineHeading">
						Learn more and contribute on GitHub
					</div>
					<a href="https://github.com/telemetryjet/telemetryjet-arduino-sdk" class="bp3-button bp3-large bp3-primary bp3-intent-primary bp3-icon-git-branch bp3-fill bp3-outlined-button">TelemetryJet Arduino SDK</a>
					<a href="https://github.com/telemetryjet/telemetryjet-cli" class="bp3-button bp3-large bp3-primary bp3-intent-primary bp3-icon-git-branch bp3-fill bp3-outlined-button">TelemetryJet CLI</a>
				</div>
			</div>
	</section>
</div>