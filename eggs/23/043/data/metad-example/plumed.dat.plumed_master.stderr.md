**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1921-959:63826] *** Process received signal ***
[fv-az1921-959:63826] Signal: Aborted (6)
[fv-az1921-959:63826] Signal code:  (-6)
[fv-az1921-959:63826] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ef5a45330]
[fv-az1921-959:63826] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ef5a9eb2c]
[fv-az1921-959:63826] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ef5a4527e]
[fv-az1921-959:63826] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ef5a288ff]
[fv-az1921-959:63826] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ef5ea5ff5]
[fv-az1921-959:63826] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ef5ebb0da]
[fv-az1921-959:63826] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ef5ea5a55]
[fv-az1921-959:63826] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ef5ea5a6f]
[fv-az1921-959:63826] [ 8] plumed_master(+0x146dd)[0x55d7674116dd]
[fv-az1921-959:63826] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ef5a2a1ca]
[fv-az1921-959:63826] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ef5a2a28b]
[fv-az1921-959:63826] [11] plumed_master(+0x15365)[0x55d767412365]
[fv-az1921-959:63826] *** End of error message ***
</pre>
{% endraw %}
