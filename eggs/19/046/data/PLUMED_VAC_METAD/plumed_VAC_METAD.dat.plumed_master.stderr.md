**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC_METAD/plumed_VAC_METAD.dat   
(download [zipped raw stdout](plumed_VAC_METAD.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: FPS LABEL=fps REFERENCE=Faidon_new_ref.pdb LIGAND=lig ANCHOR=2481 POINTS=-0.5910,0.3486,-1.6694,-0.6214,0.5475,-1.2516
Maybe a missing space or a typo?
[fv-az95-172:66042] *** Process received signal ***
[fv-az95-172:66042] Signal: Aborted (6)
[fv-az95-172:66042] Signal code:  (-6)
[fv-az95-172:66042] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb4e53b2210]
[fv-az95-172:66042] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb4e53b218b]
[fv-az95-172:66042] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb4e5391859]
[fv-az95-172:66042] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb4e5619911]
[fv-az95-172:66042] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb4e562538c]
[fv-az95-172:66042] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb4e56253f7]
[fv-az95-172:66042] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fb4e56256fd]
[fv-az95-172:66042] [ 7] plumed_master(+0xf5b5)[0x560802b315b5]
[fv-az95-172:66042] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb4e53930b3]
[fv-az95-172:66042] [ 9] plumed_master(+0xf8be)[0x560802b318be]
[fv-az95-172:66042] *** End of error message ***
</pre>
{% endraw %}
