siddhi-execution-unitconversion
======================================

The **siddhi-execution-unitconversion extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that enables conversions of length, mass, time and volume units.

Find some useful links below:

* <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion">Source code</a>
* <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion/releases">Releases</a>
* <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2">2.0.2</a>.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>io.siddhi.extension.execution.unitconversion</groupId>
        <artifactId>siddhi-execution-unitconversion</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-unitconversion/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-unitconversion/) |

---

## Features

* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mmtokm-function">MmTokm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in megameters into kilometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtoft-function">cmToft</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into feet.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtoin-function">cmToin</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into inches.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtokm-function">cmTokm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input value given in centimeters into kilometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtom-function">cmTom</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into meters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtomi-function">cmTomi</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into miles.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtomm-function">cmTomm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into millimeters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtonm-function">cmTonm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into nanometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtoum-function">cmToum</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input in centimeters into micrometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#cmtoyd-function">cmToyd</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in centimeters into yards.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#dtoh-function">dToh</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in days into hours.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#gtokg-function">gTokg</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in grams into kilograms.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#gtomg-function">gTomg</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in grams into milligrams.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#gtoug-function">gToug</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in grams into micrograms.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#htom-function">hTom</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in hours into minutes.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#htos-function">hTos</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in hours into seconds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtolt-function">kgToLT</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into imperial tons.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtost-function">kgToST</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into US tons.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtog-function">kgTog</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into grams.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtolb-function">kgTolb</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into pounds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtooz-function">kgTooz</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into ounces.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtost-function">kgTost</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into imperial stones.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kgtot-function">kgTot</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilograms into tonnes.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtocm-function">kmTocm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into centimeters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtoft-function">kmToft</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into feet.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtoin-function">kmToin</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into inches.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtom-function">kmTom</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into meters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtomi-function">kmTomi</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into miles.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtomm-function">kmTomm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into millimeters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtonm-function">kmTonm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into nanometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtoum-function">kmToum</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into micrometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#kmtoyd-function">kmToyd</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in kilometers into yards.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#ltom3-function">lTom3</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in liters into cubic meters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#ltoml-function">lToml</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in liters into milliliters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#m3tol-function">m3Tol</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in cubic meters into liters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mtocm-function">mTocm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in meters into centimeters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mtoft-function">mToft</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in meters into feet.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mtomm-function">mTomm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in meters into millimeters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mtos-function">mTos</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in minutes into seconds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mtoyd-function">mToyd</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in meters into yards.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mitokm-function">miTokm</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in miles into kilometers.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#mltol-function">mlTol</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in milliliters into liters.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#stoms-function">sToms</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in seconds into milliseconds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#stons-function">sTons</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in seconds into nanoseconds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#stous-function">sTous</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in seconds into microseconds.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#ttog-function">tTog</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in tonnes into grams.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#ttokg-function">tTokg</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the input given in tonnes into kilograms.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-unitconversion/api/2.0.2/#ytod-function">yTod</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This converts the given input in years into days.</p></div>

## How to Contribute
 
  * Please report issues at <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-unitconversion/tree/master">master branch</a>.
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 
