**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1215-275:07338] *** Process received signal ***
[fv-az1215-275:07338] Signal: Aborted (6)
[fv-az1215-275:07338] Signal code:  (-6)
[fv-az1215-275:07338] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd13d642520]
[fv-az1215-275:07338] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd13d6969fc]
[fv-az1215-275:07338] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd13d642476]
[fv-az1215-275:07338] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd13d6287f3]
[fv-az1215-275:07338] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd13daa2b9e]
[fv-az1215-275:07338] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd13daae20c]
[fv-az1215-275:07338] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd13daae277]
[fv-az1215-275:07338] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd13daae52b]
[fv-az1215-275:07338] [ 8] plumed_master(+0x14254)[0x561ef2978254]
[fv-az1215-275:07338] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd13d629d90]
[fv-az1215-275:07338] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd13d629e40]
[fv-az1215-275:07338] [11] plumed_master(+0x14eb5)[0x561ef2978eb5]
[fv-az1215-275:07338] *** End of error message ***
</pre>
{% endraw %}
