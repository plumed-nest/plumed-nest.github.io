**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1691-811:06867] *** Process received signal ***
[fv-az1691-811:06867] Signal: Aborted (6)
[fv-az1691-811:06867] Signal code:  (-6)
[fv-az1691-811:06867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3abb645330]
[fv-az1691-811:06867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3abb69eb2c]
[fv-az1691-811:06867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3abb64527e]
[fv-az1691-811:06867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3abb6288ff]
[fv-az1691-811:06867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3abbaa5ff5]
[fv-az1691-811:06867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3abbabb0da]
[fv-az1691-811:06867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3abbaa5a55]
[fv-az1691-811:06867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3abbaa5a6f]
[fv-az1691-811:06867] [ 8] plumed(+0x146dd)[0x55a4e9a496dd]
[fv-az1691-811:06867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3abb62a1ca]
[fv-az1691-811:06867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3abb62a28b]
[fv-az1691-811:06867] [11] plumed(+0x15365)[0x55a4e9a4a365]
[fv-az1691-811:06867] *** End of error message ***
</pre>
{% endraw %}
