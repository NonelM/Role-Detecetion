# Community‐Aware Roles of Nodes
Final assignment of the subject Web Analytics, focused on discovering communities and roles from two large networks (subset of (co)authors and a Flickr newtork)
# Types of roles
- Structural holes (SH)
- Diverse actors (DA)
- Community bridges (CB)
- Opinion leaders (OL)
- Community cores (CC)
1、self.community是一个list，表示点对应的community，self.community[i]=c,表示第i个node被聚合在c类别中
2、communites = [5, 88, 16, 1072, 59, 222]，表示第一个节点属于5号社区，第二个节点表示属于88号社区，第三个节点属于16号社区
3、partition的结构形式是字典{'节点号' : 社区号，'节点号' : 社区号，'节点号' : 社区号，'节点号' : 社区号，'节点号' : 社区号}
4、从图G→求best_partition→转为list即为communites



--dhihdia ddsasadifdsidsffdsfdsfasdgfd