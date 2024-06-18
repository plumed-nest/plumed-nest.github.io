**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1anr/08-IMIA/2-Production/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: SHADOW LABEL=rmsd ATOMS=rna NOPBC UPDATE=100
Maybe a missing space or a typo?
[fv-az1272-851:05204] *** Process received signal ***
[fv-az1272-851:05204] Signal: Aborted (6)
[fv-az1272-851:05204] Signal code:  (-6)
[fv-az1272-851:05204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9298442520]
[fv-az1272-851:05204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f92984969fc]
[fv-az1272-851:05204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9298442476]
[fv-az1272-851:05204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f92984287f3]
[fv-az1272-851:05204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f92988a2b9e]
[fv-az1272-851:05204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f92988ae20c]
[fv-az1272-851:05204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f92988ae277]
[fv-az1272-851:05204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f92988ae52b]
[fv-az1272-851:05204] [ 8] plumed(+0x12f48)[0x55af05834f48]
[fv-az1272-851:05204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9298429d90]
[fv-az1272-851:05204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9298429e40]
[fv-az1272-851:05204] [11] plumed(+0x131e5)[0x55af058351e5]
[fv-az1272-851:05204] *** End of error message ***
</pre>
{% endraw %}
