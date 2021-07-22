**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
(download [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip))  
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
[fv-az95-172:65985] *** Process received signal ***
[fv-az95-172:65985] Signal: Aborted (6)
[fv-az95-172:65985] Signal code:  (-6)
[fv-az95-172:65985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5450d7d210]
[fv-az95-172:65985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5450d7d18b]
[fv-az95-172:65985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5450d5c859]
[fv-az95-172:65985] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5450fe4911]
[fv-az95-172:65985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5450ff038c]
[fv-az95-172:65985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5450ff03f7]
[fv-az95-172:65985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5450ff06a9]
[fv-az95-172:65985] [ 7] plumed(+0xf47d)[0x5556c9b3f47d]
[fv-az95-172:65985] [ 8] plumed(+0x14004)[0x5556c9b44004]
[fv-az95-172:65985] [ 9] plumed(+0xf698)[0x5556c9b3f698]
[fv-az95-172:65985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5450d5e0b3]
[fv-az95-172:65985] [11] plumed(+0xf76e)[0x5556c9b3f76e]
[fv-az95-172:65985] *** End of error message ***
</pre>
{% endraw %}
