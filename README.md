<h1 align="center">Ozone Haiti 🇭🇹</h1>

<p align="center">
    <b>Ozone Haiti</b> is a starter EMR/HIS distribution tailored for healthcare facilities in Haiti.
    <br/>Built with Ozone, it includes common configurations and master data specifically designed for use in Haitian settings.
</p>

---

<br/>

<p align="center">
    <a href="https://docs.ozone-his.com/"><img src="https://raw.githubusercontent.com/ozone-his/.github/refs/heads/main/profile/ozone-logo.png" alt="Ozone" width="20%"/></a>
</p>

<h3 align="center">The Instant HIS</h3>

<p align="center">
    <br/>Engage with the Ozone community and access useful resources below:
</p>

<h3 align="center">
    <a href="https://github.com/ozone-his/">Code</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://docs.ozone-his.com/">Docs</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://talk.openmrs.org/c/software/ozone-his/70">Forum</a>&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://openmrs.slack.com/archives/C02PYQD5D0A">Chat Room</a>
</h3>

## Release Notes

<details>
  <summary><b>Version 1.1.0</b></summary>
   <ul>
    <li>Depends on:
     <ul>
      <li><a href="https://docs.ozone-his.com/users/#ozone-his-apps">Ozone 1.0.0-alpha.13</a></li>
     </ul>
    </li>
   </ul>

   <b>Specific notes</b>

   <ul>
    <li>Unified order type names in Order Basket.</li>
    <li>Upgraded esm-patient-medications-app to v9.2.3-pre.7115.</li>
    <li>Upgraded esm-patient-billing-status-app to 1.0.1-pre.27..</li>
    <li>Used OpenMRS module ERP 2.1.0.</li>
    <li>Made ozone-lamp to be a child distribution of ozone-haiti.</li>
    <li>Removed Numéro Dossier identifier from Patient registration form .</li>
    <li>Updated Ozone version to 1.0.0-alpha.13.</li>
    <li>Removed Physical_examination.json file.</li>
    <li>Added missing Odoo Addons binaries.</li>
    <li>Removed openmrs_SOAP_vSOAP_Note_autoexpand-SOAP OCL package.</li>
    <li>Updated sale_order_price_recalculation to version 10.0.1.0.1.</li>
    <li>Added display conditions privileges for ward app.</li>
  </ul>
</details>

<details>
  <summary><b>Version 1.0.0</b></summary>
   <ul>
    <li>Depends on:
     <ul>
      <li><a href="https://docs.ozone-his.com/users/#ozone-his-apps">Ozone 1.0.0-alpha.13</a></li>
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
    <li>Added Medical supply product UOMs.</li>
    <li>Fixed Ward form concepts.</li>
    <li>Set HSC specific ESMs to fixed versions.</li>
    <li>Configured IPD 'Admission Decision' concepts.</li>
    <li>Excluded 'openmrs_CIELImmunizationContent' file.</li>
    <li>Set the 'dispositionConfig.json'.</li>
    <li>Fixed Ward Admission functionality.</li>
    <li>Updated 'esm-patient-allergies-app' to 9.2.1</li>
    <li>Excluded Attachements, Laboratory and Services Queues ESMs.</li>
    <li>Added missing OCL package for IPD concepts.</li>
    <li>Removed creating the 'Tablet / fdbe907b...' dosage unit.</li>
    <li>Added encounter for capturing immunizations.</li>
  </ul>
</details>
