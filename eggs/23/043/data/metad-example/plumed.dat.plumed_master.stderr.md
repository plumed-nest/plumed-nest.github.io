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
[pkrvmpptgkbjq6m:08374] *** Process received signal ***
[pkrvmpptgkbjq6m:08374] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08374] Signal code:  (-6)
[pkrvmpptgkbjq6m:08374] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84f0245330]
[pkrvmpptgkbjq6m:08374] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84f029eb2c]
[pkrvmpptgkbjq6m:08374] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84f024527e]
[pkrvmpptgkbjq6m:08374] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84f02288ff]
[pkrvmpptgkbjq6m:08374] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84f06a5ff5]
[pkrvmpptgkbjq6m:08374] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84f06bb0da]
[pkrvmpptgkbjq6m:08374] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84f06a5a55]
[pkrvmpptgkbjq6m:08374] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84f06a5a6f]
[pkrvmpptgkbjq6m:08374] [ 8] plumed_master(+0x146dd)[0x56514d9166dd]
[pkrvmpptgkbjq6m:08374] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84f022a1ca]
[pkrvmpptgkbjq6m:08374] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84f022a28b]
[pkrvmpptgkbjq6m:08374] [11] plumed_master(+0x15365)[0x56514d917365]
[pkrvmpptgkbjq6m:08374] *** End of error message ***
</pre>
{% endraw %}
