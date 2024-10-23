**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1215-275:07277] *** Process received signal ***
[fv-az1215-275:07277] Signal: Aborted (6)
[fv-az1215-275:07277] Signal code:  (-6)
[fv-az1215-275:07277] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7faded242520]
[fv-az1215-275:07277] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7faded2969fc]
[fv-az1215-275:07277] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7faded242476]
[fv-az1215-275:07277] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7faded2287f3]
[fv-az1215-275:07277] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7faded6a2b9e]
[fv-az1215-275:07277] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7faded6ae20c]
[fv-az1215-275:07277] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7faded6ae277]
[fv-az1215-275:07277] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7faded6ae52b]
[fv-az1215-275:07277] [ 8] plumed_master(+0x14254)[0x56104d907254]
[fv-az1215-275:07277] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7faded229d90]
[fv-az1215-275:07277] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7faded229e40]
[fv-az1215-275:07277] [11] plumed_master(+0x14eb5)[0x56104d907eb5]
[fv-az1215-275:07277] *** End of error message ***
</pre>
{% endraw %}
