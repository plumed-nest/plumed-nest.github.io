**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
(download [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az95-172:60574] *** Process received signal ***
[fv-az95-172:60574] Signal: Aborted (6)
[fv-az95-172:60574] Signal code:  (-6)
[fv-az95-172:60574] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f52f1172210]
[fv-az95-172:60574] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f52f117218b]
[fv-az95-172:60574] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f52f1151859]
[fv-az95-172:60574] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f52f13d9911]
[fv-az95-172:60574] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f52f13e538c]
[fv-az95-172:60574] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f52f13e53f7]
[fv-az95-172:60574] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f52f13e56a9]
[fv-az95-172:60574] [ 7] plumed(+0xf47d)[0x556c023a047d]
[fv-az95-172:60574] [ 8] plumed(+0x14004)[0x556c023a5004]
[fv-az95-172:60574] [ 9] plumed(+0xf698)[0x556c023a0698]
[fv-az95-172:60574] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f52f11530b3]
[fv-az95-172:60574] [11] plumed(+0xf76e)[0x556c023a076e]
[fv-az95-172:60574] *** End of error message ***
</pre>
{% endraw %}
