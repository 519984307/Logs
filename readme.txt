Logs��һ��д��־�ļ��Ĺ����࣬���õ���ģʽ

�����Զ��Ե�ǰ������Ϊ��־�ļ�������ʽ���硰yyyy-MM-dd.log����ͳһ������ָ����logsDir�¡�Ϊ�˱�������ʱ��������־�ļ�Խ��Խ�࣬������ÿ�γ�������ʱ����rmLogsFile(int retainDays)��ֻ��������������־��ɾȥ�������õ���־��

//�ӿں���
void setLogsDir(const QString &dirPath);//������־�ļ�Ŀ¼
void rmLogsFile(int retainDays=0);//ɾ����־�ļ�
void writeLogs(const QString &content,LogsLevel logsLevel=INFO_LEVEL);//д��־


������ϵ��ʽ��@Ϊ-��-����(����΢��)
