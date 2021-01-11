**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
(download [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: FPS LABEL=fps REFERENCE=Faidon_new_ref.pdb LIGAND=lig ANCHOR=2481 POINTS=-0.5910,0.3486,-1.6694,-0.6214,0.5475,-1.2516
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f00b086b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f00b086b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f00b086d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f00b0ea584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f00b0ea36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f00b0ea3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f00b0ea3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f00b0856830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14142] *** End of error message ***
</pre>
{% endraw %}
