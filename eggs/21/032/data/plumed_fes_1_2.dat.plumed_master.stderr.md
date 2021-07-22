**Project ID:** [plumID:21.032]({{ '/' | absolute_url }}eggs/21/032/)  
Stderr for source:  plumed_fes_1_2.dat   
(download [zipped raw stdout](plumed_fes_1_2.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action DRMSD with label DRMSD : missing input file reference.pdb
[fv-az95-172:31132] *** Process received signal ***
[fv-az95-172:31132] Signal: Aborted (6)
[fv-az95-172:31132] Signal code:  (-6)
[fv-az95-172:31132] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f86b4e18210]
[fv-az95-172:31132] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f86b4e1818b]
[fv-az95-172:31132] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f86b4df7859]
[fv-az95-172:31132] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f86b507f911]
[fv-az95-172:31132] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f86b508b38c]
[fv-az95-172:31132] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f86b508b3f7]
[fv-az95-172:31132] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f86b508b6fd]
[fv-az95-172:31132] [ 7] plumed_master(+0xf5b5)[0x564af57185b5]
[fv-az95-172:31132] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f86b4df90b3]
[fv-az95-172:31132] [ 9] plumed_master(+0xf8be)[0x564af57188be]
[fv-az95-172:31132] *** End of error message ***
</pre>
{% endraw %}
