# Ozone Haiti 🇭🇹

**Ozone Haiti** packages common configurations and metadata to use [Ozone HIS](https://www.ozone-his.com) in Haiti.

Available commands to build and run the project:
https://docs.ozone-his.com/create-distro/#available-commands

---

<p align="center">
    <a href="https://docs.ozone-his.com/"><img src="https://www.ozone-his.com/wp-content/uploads/2021/11/Ozone-Logo.png" alt="Ozone" width="30%"/></a>
</p>

<h3 align="center">Health Information System</h3>

<p align="center">
    <br/>Engage with the Ozone community and access useful resources below:
</p>

<h3 align="center">
    <a href="https://docs.ozone-his.com/">Docs</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://talk.openmrs.org/c/software/ozone-his/70">Forum</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://openmrs.slack.com/archives/C02PYQD5D0A">Chat Room</a>
</h3>

## Release Notes

<details>
  <summary><b>Version 1.0.0</b></summary>
   <ul>
    <li>Depends on:
     <ul>
      <li><a href="https://docs.ozone-his.com/users/#ozone-his-apps">Ozone Alpha 12</a></li>
     </ul>
    </li>
   </ul>

   <b>Specific notes</b>

   <ul>
    <li>Set license to MPL 2.0.</li>
    <li>Added iniz domains.</li>
    <li>Added 'Motif de consultation' form and concepts.</li>
    <li>Added 'Examen des systemes' form and concepts.</li>
    <li>Added proof of concept for OpenMRS.</li>
    <li>Added support for Ozone HSC to depend on Ozone Haiti.</li>
    <li>Added GitHub Actions pipelines.</li>
    <li>Added '.ocd3.yml' file.</li>
    <li>Ensured successful loading of configurations.</li>
    <li>Updated 'ozone/' to 'configs/' for serving frontend configurations.</li>
    <li>Added Odoo initializer configurations.</li>
    <li>Configured encounter types with their associated forms.</li>
    <li>Configured relationship types.</li>
    <li>Used O3's default orders encounter type UUID.</li>
    <li>Used O3's default diagnosis encounter type UUID.</li>
    <li>Added and configured 'openmrs-module-orderexpansion' to support material ordering.</li>
    <li>Added esm-patient-billing-status-app to the assemble config.</li>
    <li>Enabled rebuilding of OpenMRS frontend if necessary.</li>
    <li>Deleted medical supply order type.</li>
    <li>Added imaging order type and imaging concept class.</li>
    <li>Added systolic and diastolic bp as members of vital signs.</li>
    <li>Fixed 'ampathformstransalations' config.</li>
    <li>Removed same as mappings.</li>
    <li>Added ward admission form.</li>
    <li>Added medical supply order app to Ozone Haiti.</li>
    <li>Updated concept class for test order type.</li>
    <li>README as per Ozone's rebranding.</li>
    <li>Reworded Triage Level concept.</li>
    <li>Added display values to order types.</li>
    <li>Added 'Procedure' order type at Haiti level.</li>
    <li>Added order basket action menu button to the ward-patient workspace action menu.</li>
    <li>Fixed IPD admission form and added encounter types.</li>
    <li>Set default locale and allowed locales to French.</li>
    <li>Included Odoo auth_providers initializer config.</li>
    <li>Renamed OpenMRS frontend config.</li>
    <li>Added ward app to the Ozone Haiti Distro.</li>
    <li>Included initializer_config.json so Odoo can load auth_providers.</li>
    <li>Added emrapi, bed-management modules to OZ Haiti.</li>
    <li>Fixed drugs dosing units.</li>
    <li>Removed 'Same as' mappings.</li>
    <li>Fixed Cause of Death Data class and Answers.</li>
    <li>Override ESMs to use latest O3.</li>
    <li>Used Order Expansion module 1.0.0.</li>
    <li>Added Medical supply product UOMs</li>
  </ul>
</details>
