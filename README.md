# -package 积分;

public class jifen {
	String leixing;
	int jifen;
	public void show(){
		if (leixing.equals("金卡")&&jifen>=1000||leixing.equals("普卡")&&jifen>=5000) {
			jifen+=jifen+500;
			System.out.println("积分："+jifen+",卡类型"+leixing);
			System.out.println("回馈500分");
		}
	}
}
