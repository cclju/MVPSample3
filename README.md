# MVPSample3
Activity被系统重启后Presenter的处理方式

不同于 Contract 的方式，
通过 BaseActivity implements MvpView, BasePresenter<V extends MvpView> implements Presenter<V>,
子类在分别写各自 ILoginView, ILoginPresenter 接口, 实现 mvp
