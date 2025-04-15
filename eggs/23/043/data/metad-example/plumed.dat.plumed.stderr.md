**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[fv-az1921-959:63810] *** Process received signal ***
[fv-az1921-959:63810] Signal: Aborted (6)
[fv-az1921-959:63810] Signal code:  (-6)
[fv-az1921-959:63810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1eb8c45330]
[fv-az1921-959:63810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1eb8c9eb2c]
[fv-az1921-959:63810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1eb8c4527e]
[fv-az1921-959:63810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1eb8c288ff]
[fv-az1921-959:63810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1eb90a5ff5]
[fv-az1921-959:63810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1eb90bb0da]
[fv-az1921-959:63810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1eb90a5a55]
[fv-az1921-959:63810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1eb90a5a6f]
[fv-az1921-959:63810] [ 8] plumed(+0x146dd)[0x563a927626dd]
[fv-az1921-959:63810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1eb8c2a1ca]
[fv-az1921-959:63810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1eb8c2a28b]
[fv-az1921-959:63810] [11] plumed(+0x15365)[0x563a92763365]
[fv-az1921-959:63810] *** End of error message ***
</pre>
{% endraw %}
