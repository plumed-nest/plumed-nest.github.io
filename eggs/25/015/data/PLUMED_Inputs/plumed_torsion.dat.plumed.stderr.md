**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmkj6or:04173] *** Process received signal ***
[runnervmkj6or:04173] Signal: Aborted (6)
[runnervmkj6or:04173] Signal code:  (-6)
[runnervmkj6or:04173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3245c45330]
[runnervmkj6or:04173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3245c9eb2c]
[runnervmkj6or:04173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3245c4527e]
[runnervmkj6or:04173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3245c288ff]
[runnervmkj6or:04173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32460a5ff5]
[runnervmkj6or:04173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32460bb0da]
[runnervmkj6or:04173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32460a5a55]
[runnervmkj6or:04173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32460a5a6f]
[runnervmkj6or:04173] [ 8] plumed(+0x146dd)[0x5641257806dd]
[runnervmkj6or:04173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3245c2a1ca]
[runnervmkj6or:04173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3245c2a28b]
[runnervmkj6or:04173] [11] plumed(+0x15365)[0x564125781365]
[runnervmkj6or:04173] *** End of error message ***
</pre>
{% endraw %}
