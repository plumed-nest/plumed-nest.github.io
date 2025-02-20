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
[fv-az1911-722:10087] *** Process received signal ***
[fv-az1911-722:10087] Signal: Aborted (6)
[fv-az1911-722:10087] Signal code:  (-6)
[fv-az1911-722:10087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5812845330]
[fv-az1911-722:10087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f581289eb2c]
[fv-az1911-722:10087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f581284527e]
[fv-az1911-722:10087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58128288ff]
[fv-az1911-722:10087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5812ca5ff5]
[fv-az1911-722:10087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5812cbb0da]
[fv-az1911-722:10087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5812ca5a55]
[fv-az1911-722:10087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5812ca5a6f]
[fv-az1911-722:10087] [ 8] plumed(+0x146dd)[0x5559ef98f6dd]
[fv-az1911-722:10087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f581282a1ca]
[fv-az1911-722:10087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f581282a28b]
[fv-az1911-722:10087] [11] plumed(+0x15365)[0x5559ef990365]
[fv-az1911-722:10087] *** End of error message ***
</pre>
{% endraw %}
