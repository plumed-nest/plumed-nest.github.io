**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1701-508:64900] *** Process received signal ***
[fv-az1701-508:64900] Signal: Aborted (6)
[fv-az1701-508:64900] Signal code:  (-6)
[fv-az1701-508:64900] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda31a45330]
[fv-az1701-508:64900] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda31a9eb2c]
[fv-az1701-508:64900] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda31a4527e]
[fv-az1701-508:64900] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda31a288ff]
[fv-az1701-508:64900] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda31ea5ff5]
[fv-az1701-508:64900] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda31ebb0da]
[fv-az1701-508:64900] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda31ea5a55]
[fv-az1701-508:64900] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda31ea5a6f]
[fv-az1701-508:64900] [ 8] plumed_master(+0x146dd)[0x5583ee3756dd]
[fv-az1701-508:64900] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda31a2a1ca]
[fv-az1701-508:64900] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda31a2a28b]
[fv-az1701-508:64900] [11] plumed_master(+0x15365)[0x5583ee376365]
[fv-az1701-508:64900] *** End of error message ***
</pre>
{% endraw %}
