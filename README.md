2016��5��26��17:54:15
������һ������imagelistGUIС���ߣ��ܺ�����ģ���ҿ������ԡ�

2016��5��26��17:06:15
��θ����������˼�������
text_process.py
'''
������TxtToCsv����
�������ܣ���.txt�ļ�ת����csv���������ֻ�����ض����������ض�����.txtʹ�ã�
        ����ͨ�ã�ȱ���ǲ�����������
���������txt----.txt�ļ�
         csv----.csv�ļ�
'''
'''
������Find����
�������ܣ�Ѱ�Ұ����ض��ļ������ļ���
���������dirpath----���ݼ�·��
         num----�ļ��е�����
'''
Picture.py
'''
������DataAugmentFlip����
�������ܣ�����������,��Ҫ��ͨ����ת
���������dir_path----ͼƬ��·��
         num----һ����ֵ�������ļ�����num�ļ��ڵ�ͼƬ
         targetnum----Ŀ��������������������ͼƬ����
'''
'''
������DataAugmentCrop()
�������ܣ�ͨ�����������������
���������picdir----ͼƬ���ļ���·��
         leftup----�Ƿ�����ϽǼ���,Ĭ��
         leftdown----�Ƿ�����½Ǽ���
         rightup----�Ƿ�����ϽǼ���
         rightdown----�Ƿ�����½Ǽ���
         new_w----���ú�ͼƬ����
         new_h----���ú�ͼƬ����
         picnum----����С��picnum���ļ���
         addnum----��������addnum*model
         targetnum----Ŀ��������������������ͼƬ����
'''
'''
������DataBalance����
�������ܣ�ƽ�����ݼ�����ֻ�Ǵ��ԵĲ�����ʮ�־�ȷ
���������dirpath----���ݼ�·��
         baisnum----��׼����������Ҫ��ƽ����������Ҫ˵��һ�£�������ֻ���������ݵ�����
         ��˴���baisnum���ļ��в�û�д���,��õ�2�ı���
		 new_h----������ͼƬ�߶�
		 new_w----������ͼƬ����
'''

<<<<<<< HEAD
2016��5��13��09:37:58
No1.CreatImagelist.py  
������ǳ����ҵ��֣�����ȴ�ǳ����ã����Բ�������ǩ��ͼƬ·���б�

No2.dir_to_picture.py  
�����Ҫ�����ǽ��ֺ����ͼƬ���ڶ���ļ����У�����������һ���ļ����У�����ɾ��

No3.extract_feacture.py
�������Ҫ������������ȡͼƬ����������������������ļ�

No4.feature_class.py
���Ҳ���������࣬�������ÿ��ͼƬ��һһ�Աȣ����������С���ԣ����������������ű�̫�˷�ʱ��

No5.Math.py ���������������1������cos���룻2���Ƚ��������Ĵ�С

No6.text_process.py

'''
������name_convert����
���ܣ��ɼ�����ͼƬ��������ʱ���ַ��ͣ�����ת����000000001��ʽ
     ������б������ŵ�128*128��ͬʱת�ɻҶ�ͼ
����Ĳ�����dir_name  ֻ���ͼƬ���ļ�������
           dir_name_save  �������ļ���
'''

'''
������creat_imagelist_NoLabel()
���ܣ��ǰ�һ���ļ���������ͼƬд��һ��imagelist.txt�ļ���
���������dir_path ���ͼƬ���ļ���
         imagelist_path,����·��
'''

'''
������clean_image()
���ܣ����������û�м�⵽�������޳�
���������imagelist---���������·���б�
         dir_path_save---����·��
'''

'''
������CreatImageListWithLabel()
���ܣ�����caffe imagelist.txt �ļ������ļ�����ǩ
���������dir_path ͼƬ·����һ��Ϊ����ܶ����ļ��еĸ��ļ���·��
         imgelist ����ļ�·��Ĭ���ǵ�ǰ�ļ�����
'''

'''
������load()
�������ܣ���һ���ı��ļ��е�������ȡ��һ��list��
���������file_path----�ı��ļ�·��
'''

'''
������Pic_Num()
���ܣ�ͳ���ļ�����ͼƬ������
���������dir_path----����ͼƬ���ļ���·��
'''

'''
������ReName����
���ܣ����°�˳�������ļ������ڶԸ����ļ�ɾ���󣬶��ļ�������������
���������dir_path----�����ļ������ļ��еģ����ļ���·��

No7.Visualize.py   ����Ȩ�ؿ��ӻ���δ��
'''
������vis_square()
�������ܣ�һ����ʾ��������
���������data
        out----����ͼƬ��·��
'''
'''
������VisualWeights()
�������ܣ����ݲ�������ʾ��Ӧ��Ȩ��
���������layer_name----������
         net----��ʼ���������
         out----����ͼƬ��·��
'''
'''
������VisualWeight()
�������ܣ����ݲ�������ʾ��Ӧ��Ȩ��
���������layer_name----������
         net----��ʼ���������
'''
'''
������VisualBlob()
�������ܣ����ӻ�Blob
���������net----��ʼ���������
         layer_name----�������
'''
'''
������VisualBlobs()
�������ܣ���������Blobs
���������net----��ʼ���������
         out----����·��
'''
'''
������VisualLayerShape()
��������ʾ������ֺ���״
���������net----��ʼ���������
'''
'''
������VisualLayerWeightShape()
�������ܣ���ʾ����Ȩ�ص���״
���������net----��ʼ���������
'''
No8.Picture.py
'''
������Resize����
�������ܣ���������ͼƬ��С
���������dir_path----�ļ���·��
         new_h��new_w----��ͼƬ�ĸ߶ȺͿ���
'''
'''
������DataAugment����
�������ܣ�����������
���������dir_path----ͼƬ��·��
'''

No9.draw.py
'''
������Draw����
�������ܣ�����WU_lfw_test.py ������result.txt�ļ���ͼ
���������file_path
'''
'''
������Draw_His����
�������ܣ�����ͼƬ���һЩͳ����Ϣ��������ֱ��ͼ
���������dir_path
'''

No10.CreatValSet.py
'''
������TestPair����
�������ܣ����������֤���ԣ���������������
���������dir_path----��֤����
         class_num----��֤�������
         leftlist----left.txt ·��
         rightlist----right.txt ·��
         label----��ǩ·��
         pos_num----����������
         neg_num----����������
'''

No11.LfwTest.py  ��lfw���ϲ���ģ��

No12.process.py
'''
������renamedir����
�������ܣ��������ļ��У���һ��˳��
���������dir_path----�������ļ��е�·��
         start   ----��ʼ���
'''
'''
������Rmovedir����
�������ܣ�ɾ���ļ������ļ�����һ���������ļ���
���������dir_path----�������ļ��е�·��
         num----��ֵ�����ļ�����С�ڵ���num���ļ���ɾ��
'''
'''
������ Romvepath����
�������ܣ�ɾ��һ��imagelist�в����ڵ�·��
���������inputlist,outputlist
'''
'''
������Rmovepath_pair()
�������ܣ��ɶ�ɾ���ļ��в����ڵ�·��
���������input1,input2,inlabel,output1,output2,outlabel
'''
'''
������TestPair����
�������ܣ������ݿ�����ѡ��������
���������dir_path----���ͼƬ��·��
         class_num----�������
         neg_num----��������
         pos_num----��������
         leftlist
         rightlist
         label
'''
'''
������Select_K_MaxMin()
�������ܣ�����ļ�����ͼƬ����������С��ǰK���ļ���·��
���������dir_path----ͼƬ��·��
         model----ѡ���������СĬ��
         K----ǰK��
'''
=======
   ������Ҫ������ʹ��caffe�Ǳ�д��һЩС�ű��������������ѵ�ʹ�ã�Ҳϣ�������С�������ҷ��������Ѿ���ÿ�������Ĺ��ܺ������������˵�����������ʹ���ϵ�������Ը��ҷ��͵����ʼ�451413025@qq.com��
   �������vedio��һ��˵����vedio���������ȡ���ֿ�������ļ�������޷����У��Ǹ�������Լ�����Ŀ��д�Ĳ��֣�������featue.exe�ļ�������������Լ���д������ȡ���֣�Ȼ���޸�main.py�ļ����ɡ�
   ���ڸ���֮��........
>>>>>>> origin/master