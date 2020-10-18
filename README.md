# 说明

提供Balzor以及AntDesignBlazor中常用的代码片段

# 安装

# 支持的代码片段

## Blazor

### C#
|快捷方式|代码示例|
|----|----|
|cprop  | ``` [CascadingParameter] public int MyProperty { get; set; }``` |
|eprop  | ```[Parameter] public EventCallback<int> MyProperty { get; set; }``` |
|iprop  | ```[Inject] public int MyProperty { get; set; }``` |
|pprop  | ```[Parameter] public int MyProperty { get; set; }``` |
| ihttp | ```[Inject] public HttpClient Http { get; set; }``` |

## AntDesign

### C#

|快捷方式|代码示例|
|----|----|
|iconfirm  | ```[Inject] public ConfirmService ConfirmSrv { get; set; }``` |
| idrawer | ```[Inject] public DrawerService DrawerSrv { get; set; }``` |
| imessage | ```[Inject] public MessageService MsgSrv { get; set; }``` |
| imodal| ```[Inject] public ModalService ModalSrv { get; set; }``` |

### Html

|快捷方式|代码示例|
|----|----|
| abtn | ```<Button OnClick="OnClick">按钮</Button>``` |
| abtn-primary | ```<Button OnClick="OnClick" Type="primary">按钮</Button>``` |
| abtn-dashed | ```<Button OnClick="OnClick" Type="dashed">按钮</Button>``` |
| abtn-link | ```<Button OnClick="OnClick" Type="link">按钮</Button>``` |

