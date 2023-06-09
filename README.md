# api-paint4art
Paint4.art API document
## 通过描述生成图片

<a id=通过描述生成图片1404> </a>

### 基本信息

**Path：** https://cloud.paint4.art/aipaint

**Method：** POST

**接口描述：**

入参：
```Java

{
    "desc":"一只狗",
    "model":"Stable_Diffusion"
}
```
出参：
```Java
{
    "code": 1000,
    "msg": "success",
    "data": {
        "pic_id": 2153,
        "pic_url": "https://paint4art.oss-cn-beijing.aliyuncs.com/aiimages/8VggNTA9NP.jpg"
    }
}
```

### 请求参数

**Headers**

| 参数名称      | 参数值           | 是否必须 | 示例                                                         | 备注  |
| ------------- | ---------------- | -------- | ------------------------------------------------------------ | ----- |
| Content-Type  | application/json | 是       |                                                              |       |

**Body** 
<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> desc</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">描述信息</span></td><td key=5></td></tr>
               </tbody>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> model</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">模型选择</span></td><td key=5></td></tr>
               </tbody>
              </table>


### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>number</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>json</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">url地址</span></td><td key=5></td></tr>
               </tbody>
              </table>


# 
