**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[fv-az1344-582:68628] *** Process received signal ***
[fv-az1344-582:68628] Signal: Aborted (6)
[fv-az1344-582:68628] Signal code:  (-6)
[fv-az1344-582:68628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd02fc45330]
[fv-az1344-582:68628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd02fc9eb2c]
[fv-az1344-582:68628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd02fc4527e]
[fv-az1344-582:68628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd02fc288ff]
[fv-az1344-582:68628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0300a5ff5]
[fv-az1344-582:68628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0300bb0da]
[fv-az1344-582:68628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0300a5a55]
[fv-az1344-582:68628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0300a5a6f]
[fv-az1344-582:68628] [ 8] plumed(+0x146dd)[0x55f2d127b6dd]
[fv-az1344-582:68628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd02fc2a1ca]
[fv-az1344-582:68628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd02fc2a28b]
[fv-az1344-582:68628] [11] plumed(+0x15365)[0x55f2d127c365]
[fv-az1344-582:68628] *** End of error message ***
</pre>
{% endraw %}
