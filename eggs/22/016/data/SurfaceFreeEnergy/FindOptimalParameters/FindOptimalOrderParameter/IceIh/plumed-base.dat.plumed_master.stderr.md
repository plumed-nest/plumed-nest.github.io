**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[fv-az1215-275:07216] *** Process received signal ***
[fv-az1215-275:07216] Signal: Aborted (6)
[fv-az1215-275:07216] Signal code:  (-6)
[fv-az1215-275:07216] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbf9f042520]
[fv-az1215-275:07216] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbf9f0969fc]
[fv-az1215-275:07216] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbf9f042476]
[fv-az1215-275:07216] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbf9f0287f3]
[fv-az1215-275:07216] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbf9f4a2b9e]
[fv-az1215-275:07216] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbf9f4ae20c]
[fv-az1215-275:07216] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbf9f4ae277]
[fv-az1215-275:07216] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbf9f4ae52b]
[fv-az1215-275:07216] [ 8] plumed_master(+0x14254)[0x5569a0fb0254]
[fv-az1215-275:07216] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbf9f029d90]
[fv-az1215-275:07216] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbf9f029e40]
[fv-az1215-275:07216] [11] plumed_master(+0x14eb5)[0x5569a0fb0eb5]
[fv-az1215-275:07216] *** End of error message ***
</pre>
{% endraw %}
