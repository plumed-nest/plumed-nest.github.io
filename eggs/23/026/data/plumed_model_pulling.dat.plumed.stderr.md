**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1691-811:07066] *** Process received signal ***
[fv-az1691-811:07066] Signal: Aborted (6)
[fv-az1691-811:07066] Signal code:  (-6)
[fv-az1691-811:07066] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb246a45330]
[fv-az1691-811:07066] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb246a9eb2c]
[fv-az1691-811:07066] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb246a4527e]
[fv-az1691-811:07066] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb246a288ff]
[fv-az1691-811:07066] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb246ea5ff5]
[fv-az1691-811:07066] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb246ebb0da]
[fv-az1691-811:07066] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb246ea5a55]
[fv-az1691-811:07066] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb246ea5a6f]
[fv-az1691-811:07066] [ 8] plumed(+0x146dd)[0x55db5fc856dd]
[fv-az1691-811:07066] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb246a2a1ca]
[fv-az1691-811:07066] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb246a2a28b]
[fv-az1691-811:07066] [11] plumed(+0x15365)[0x55db5fc86365]
[fv-az1691-811:07066] *** End of error message ***
</pre>
{% endraw %}
