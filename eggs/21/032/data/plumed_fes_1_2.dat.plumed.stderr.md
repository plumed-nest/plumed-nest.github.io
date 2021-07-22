**Project ID:** [plumID:21.032]({{ '/' | absolute_url }}eggs/21/032/)  
Stderr for source:  plumed_fes_1_2.dat   
(download [zipped raw stdout](plumed_fes_1_2.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action DRMSD with label DRMSD : missing input file reference.pdb
[fv-az95-172:31124] *** Process received signal ***
[fv-az95-172:31124] Signal: Aborted (6)
[fv-az95-172:31124] Signal code:  (-6)
[fv-az95-172:31124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f10c5f46210]
[fv-az95-172:31124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f10c5f4618b]
[fv-az95-172:31124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f10c5f25859]
[fv-az95-172:31124] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f10c61ad911]
[fv-az95-172:31124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f10c61b938c]
[fv-az95-172:31124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f10c61b93f7]
[fv-az95-172:31124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f10c61b96a9]
[fv-az95-172:31124] [ 7] plumed(+0xf47d)[0x55d40ba2147d]
[fv-az95-172:31124] [ 8] plumed(+0x14004)[0x55d40ba26004]
[fv-az95-172:31124] [ 9] plumed(+0xf698)[0x55d40ba21698]
[fv-az95-172:31124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f10c5f270b3]
[fv-az95-172:31124] [11] plumed(+0xf76e)[0x55d40ba2176e]
[fv-az95-172:31124] *** End of error message ***
</pre>
{% endraw %}
