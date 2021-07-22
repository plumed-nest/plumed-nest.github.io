**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC_METAD/plumed_VAC_METAD.dat   
(download [zipped raw stdout](plumed_VAC_METAD.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: FPS LABEL=fps REFERENCE=Faidon_new_ref.pdb LIGAND=lig ANCHOR=2481 POINTS=-0.5910,0.3486,-1.6694,-0.6214,0.5475,-1.2516
Maybe a missing space or a typo?
[fv-az95-172:66034] *** Process received signal ***
[fv-az95-172:66034] Signal: Aborted (6)
[fv-az95-172:66034] Signal code:  (-6)
[fv-az95-172:66034] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2666adb210]
[fv-az95-172:66034] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2666adb18b]
[fv-az95-172:66034] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2666aba859]
[fv-az95-172:66034] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2666d42911]
[fv-az95-172:66034] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2666d4e38c]
[fv-az95-172:66034] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2666d4e3f7]
[fv-az95-172:66034] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2666d4e6a9]
[fv-az95-172:66034] [ 7] plumed(+0xf47d)[0x55db4cdc847d]
[fv-az95-172:66034] [ 8] plumed(+0x14004)[0x55db4cdcd004]
[fv-az95-172:66034] [ 9] plumed(+0xf698)[0x55db4cdc8698]
[fv-az95-172:66034] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2666abc0b3]
[fv-az95-172:66034] [11] plumed(+0xf76e)[0x55db4cdc876e]
[fv-az95-172:66034] *** End of error message ***
</pre>
{% endraw %}
