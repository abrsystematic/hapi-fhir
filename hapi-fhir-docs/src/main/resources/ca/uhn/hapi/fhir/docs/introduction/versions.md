# FHIR and HAPI FHIR Versions

The following table shows the various versions of the HAPI FHIR library, and the versions of the FHIR standard that they support. Note that support for stable releases of FHIR are shown in <span style="background: #CEC; padding: 3px;">GREEN</span> and support for draft pre-release versions of FHIR are shown in <span style="background: #EEB; padding: 3px;">YELLOW</span>.

Note also that after the release of the FHIR DSTU2 specification, the FHIR
    standard itself stopped using the DSTUx naming scheme, in favour or naming new releases STUx or simply Rx. Because HAPI FHIR already had draft support for what was then called DSTU3 at this time, we did not update our naming conventions until R4 in order to avoid breaking existing users' code. From the perspective of a user of HAPI FHIR, consider the terms DSTU3 / STU3 / R3 to be interchangeable.

<table class="table table-condensed">
    <thead>
    <tr>
        <td><b>HAPI Version</b></td>
        <td><b>Min JDK</b></td>
        <td><b>DSTU1</b></td>
        <td><b>DSTU2</b></td>
        <td><b>DSTU2.1</b></td>
        <td><b>DSTU3</b></td>
        <td><b>R4</b></td>
        <td><b>R5</b></td>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>HAPI FHIR 1.1</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #EEB;">0.5.0<span class="download-version-hash">-5843</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 1.2</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #EEB;">0.5.0<span class="download-version-hash">-5843</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 1.3</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 1.4</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #EEB;">1.3.0<span class="download-version-hash">-7602</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 1.5</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #EEB;">1.4.0<span class="download-version-hash">-8138</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 1.6</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #EEB;">1.4.0<span class="download-version-hash">-8636</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.0</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #EEB;">1.6.0<span class="download-version-hash">-9663</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.1</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #DDD;"></td>
        <td style="background: #EEB;">1.7.0<span class="download-version-hash">-10129</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.2</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #EEB;">1.8.0<span class="download-version-hash">-10528</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.3</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #EEB;">1.9.0<span class="download-version-hash">-11501</span></td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.4</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 2.5</td>
        <td>JDK6</td>
        <td style="background: #CEC;">0.0.82</td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #DDD;"></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.0.0</td>
        <td>JDK7</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.1.0<span class="download-version-hash">-12370</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.1.0</td>
        <td>JDK7</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.1.0<span class="download-version-hash">-12370</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.2.0</td>
        <td>JDK7</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.2.0<span class="download-version-hash">-12917</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.3.0</td>
        <td>JDK7</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.2.0<span class="download-version-hash">-13271</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.4.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.4.0<span class="download-version-hash">-13732</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.5.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.4.0<span class="download-version-hash">-13732</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.6.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #EEB;">3.6.0<span class="download-version-hash">-1202b2eed0f</span></td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.7.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #CEC;">4.0.0</td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 3.8.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #CEC;">4.0.0</td>
        <td style="background: #DDD;"></td>
    </tr>
    <tr>
        <td>HAPI FHIR 4.0.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.1</td>
        <td style="background: #CEC;">4.0.0</td>
        <td style="background: #EEB;">4.1.0<span class="download-version-hash">-e0e3caf9ba</span></td>
    </tr>
    <tr>
        <td>HAPI FHIR 4.1.0</td>
        <td>JDK8</td>
        <td style="background: #DDD;"></td>
        <td style="background: #CEC;">1.0.2</td>
        <td style="background: #EEB;">1.4.0</td>
        <td style="background: #CEC;">3.0.2</td>
        <td style="background: #CEC;">4.0.1</td>
        <td style="background: #EEB;">4.1.0<span class="download-version-hash">-1a7623d866</span></td>
    </tr>
    </tbody>
</table>
