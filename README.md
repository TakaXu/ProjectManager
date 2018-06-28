Houdini Python Panel
把文件夹整个复制进文档/Houdini XX.X/scripts/python
新建一个interface
Script：
from ProjectManager import project
reload(project)

def createInterface():
  return project.ProjectManager()
