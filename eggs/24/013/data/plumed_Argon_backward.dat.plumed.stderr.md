**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1947-163:60813] *** Process received signal ***
[fv-az1947-163:60813] Signal: Aborted (6)
[fv-az1947-163:60813] Signal code:  (-6)
[fv-az1947-163:60813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3750245330]
[fv-az1947-163:60813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f375029eb2c]
[fv-az1947-163:60813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f375024527e]
[fv-az1947-163:60813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37502288ff]
[fv-az1947-163:60813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37506a5ff5]
[fv-az1947-163:60813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37506bb0da]
[fv-az1947-163:60813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37506a5a55]
[fv-az1947-163:60813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37506a5a6f]
[fv-az1947-163:60813] [ 8] plumed(+0x146dd)[0x557d6b0446dd]
[fv-az1947-163:60813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f375022a1ca]
[fv-az1947-163:60813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f375022a28b]
[fv-az1947-163:60813] [11] plumed(+0x15365)[0x557d6b045365]
[fv-az1947-163:60813] *** End of error message ***
</pre>
{% endraw %}
