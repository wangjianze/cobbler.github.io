---
layout: manpage
title: Platform Support
meta: 2.8.0
---

Cobbler currently supports importing a wide array of operating systems from many vendors. However, since Cobbler has a history rooted in Linux based operating systems, support for them is definitely the strongest. For others, the level of support varies from very good to requiring a lot of manual steps to get things working smoothly. As such, there is strong motivation to differentiate between classes of support for various platforms while remaining strong in a few key platforms that are seen as the Cobbler “target audience”.

The Cobbler project differentiates platform targets into three tiers:

* Tier 1 - Fully functional (hosting & provisioning)
* Tier 2 - Fully functional (provisioning)
* Tier 3 - Experimantal (provisioning)


Key:

<ul>
 <li><i class="icon-ok-sign text-success"></i> Fully functional</li>
 <li><i class="icon-wrench"></i> Experimental</li>
 <li><i class="icon-ban-circle text-error"></i> Not supported</li>
</ul>


## Tier 1 platforms


<table class="table table-hover">
 <tr>
  <td class=""></td>
  <td class=""></td>
  <td class="center span1">Packages</td>
  <td class="center span1">Import</td>
  <td class="center span1">PXE</td>
  <td class="center span1">Build ISO</td>
  <td class="center span1">Kickstarts</td>
  <td class="center span1">Snippets</td>
 </tr>
 <tr>
  <td colspan="7">Red Hat</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Fedora 18</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Fedora 19</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Fedora 20</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">RHEL / CentOS 7</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td colspan="7">SuSE</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">openSUSE 12.3</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">openSUSE 13.1</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
</table>



## Tier 2 platforms

<table class="table table-hover">
 <tr>
  <td class=""></td>
  <td class=""></td>
  <td class="center span1">Packages</td>
  <td class="center span1">Import</td>
  <td class="center span1">PXE</td>
  <td class="center span1">Build ISO</td>
  <td class="center span1">Kickstarts/Snippets</td>
 </tr>
 <tr>
  <td colspan="7">Red Hat</td>
 </tr>
 <tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">RHEL/CentOS 4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">RHEL/CentOS 5</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">RHEL/CentOS 6</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
 </tr>
 <tr>
  <td colspan="7">Ubuntu</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Lucid</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Oneiric</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Precise</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Quantal</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Raring</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Saucy</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td colspan="7">Debian</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Squeeze</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Wheezy</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td colspan="7">SuSE</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">OpenSuSE 11.2</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">OpenSuSE 11.3</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">OpenSuSE 11.4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">OpenSuSE 12.1</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">OpenSuSE 12.2</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 10 sp4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 11</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 11 sp1</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 11 sp2</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 11 sp3</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">SLES 12</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
</table>


## Tier 3 platforms

<table class="table table-hover">
 <tr>
  <td class=""></td>
  <td class=""></td>
  <td class="center span1">Packages</td>
  <td class="center span1">Import</td>
  <td class="center span1">PXE</td>
  <td class="center span1">Build ISO</td>
  <td class="center span1">Kickstarts/Snippets</td>
 </tr>
<tr>
 <tr>
  <td colspan="7">VMware</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESX 4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESXi 4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESXi 5</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESXi 5.1</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESXi 5.5</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">ESXi 6</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td colspan="7">FreeBSD</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">8.2</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">8.3</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">8.4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">9.0</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td colspan="7">Xen</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">XCP 1.6</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">XenServer 6.2</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>
 <tr>
  <td colspan="7">Nexenta</td>
 </tr>
 <tr>
  <td class="span2"></td>
  <td class="span2">Nexenta 4</td>
  <td class="center span1"><i class="icon-ok-sign text-success"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-wrench"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
  <td class="center span1"><i class="icon-ban-circle text-error"></i></td>
 </tr>


</table>

<div class="alert alert-info alert-block"><b>Note:</b> This list does not include support for images, which can be just about any OS.</div>