**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1720-841:08794] *** Process received signal ***
[fv-az1720-841:08794] Signal: Aborted (6)
[fv-az1720-841:08794] Signal code:  (-6)
[fv-az1720-841:08794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3891445330]
[fv-az1720-841:08794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f389149eb2c]
[fv-az1720-841:08794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f389144527e]
[fv-az1720-841:08794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38914288ff]
[fv-az1720-841:08794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38918a5ff5]
[fv-az1720-841:08794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38918bb0da]
[fv-az1720-841:08794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38918a5a55]
[fv-az1720-841:08794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38918a5a6f]
[fv-az1720-841:08794] [ 8] plumed(+0x146dd)[0x55da5e9a26dd]
[fv-az1720-841:08794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f389142a1ca]
[fv-az1720-841:08794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f389142a28b]
[fv-az1720-841:08794] [11] plumed(+0x15365)[0x55da5e9a3365]
[fv-az1720-841:08794] *** End of error message ***
</pre>
{% endraw %}
