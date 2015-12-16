# stage-1--last-sprint
第一阶段第五次总结：这个阶段最后一个部分是对这部分的内容的容错，当用户输入非法字符会出现错误，当用户不答题也会出现错误，这一次就是为了去解决这两部分的问题。具体的代码如下：if(str2==null || str2.equalsIgnoreCase(""))
						{
					Toast.makeText(TianKong.this, "你没有输入答案，跳到下一题", 1).show();
						}
				else if(str2.matches("^[a-zA-Z]*"))
				{
					Toast.makeText(TianKong.this, "你输入的格式错误，跳到下一题", 1).show();
				}
