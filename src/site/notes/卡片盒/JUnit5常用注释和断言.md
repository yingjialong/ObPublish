---
{"dg-publish":true,"dg-permalink":"/ObPublish/OP1666080330","permalink":"/ObPublish/OP1666080330/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false,"dgShowInlineTitle":false}
---


## JUnit 5 注解

^c56895

<table id="cqtlB"><tbody><tr><td><p id="u0c281092"><strong><span>注解</span></strong></p></td><td><p id="u5d999114"><strong><span>描述</span></strong></p></td></tr><tr><td><p id="u55057081"><span>@Test</span></p></td><td><p id="u4811e3f9"><span>表示方法是一种测试方法。与 JUnit 4 的@Test 注解不同，此注释不会声明任何属性</span></p></td></tr><tr><td><p id="u9554be3c"><span>@ParameterizedTest</span></p></td><td><p id="u5f67df3b"><span>表示方法是参数化测试</span></p></td></tr><tr><td><p id="ubbeb6a03"><span>@RepeatedTest</span></p></td><td><p id="u4bc190a0"><span>表示方法是重复测试模板</span></p></td></tr><tr><td><p id="u2db2677b"><span>@TestFactory</span></p></td><td><p id="ud0fde8a2"><span>表示方法是动态测试的测试工程</span></p></td></tr><tr><td><p id="u8cc3d081"><span>@TestInstance</span></p></td><td><p id="ucf212ea6"><span>用于配置测试实例生命周期</span></p></td></tr><tr><td><p id="u6bb3b722"><span>@TestTemplate</span></p></td><td><p id="u89f5b661"><span>表示方法是为多次调用的测试用例的模板</span></p></td></tr><tr><td><p id="uefaf26b0"><span>@DisplayName</span></p></td><td><p id="ua103a54e"><span>为测试类或者测试方法自定义一个名称</span></p></td></tr><tr><td><p id="u206b77a7"><span>@BeforeEach</span></p></td><td><p id="u5004e892"><span>表示方法在每个测试方法运行前都会运行</span></p></td></tr><tr><td><p id="u63e290fa"><span>@AfterEach</span></p></td><td><p id="u538dac3b"><span>表示方法在每个测试方法运行之后都会运行</span></p></td></tr><tr><td><p id="u1515be91"><span>@BeforeAll</span></p></td><td><p id="uf5e8f723"><span>表示方法在所有测试方法之前运行，注意使用该注解的方法</span><strong><span>必须返回 void</span></strong><span>、访问级别</span><strong><span>不允许为 private</span></strong><span>，且必须声明为</span><strong><span>静态 (static) 方法</span></strong></p></td></tr><tr><td><p id="u425d0de8"><span>@AfterAll</span></p></td><td><p id="ub4c366df"><span>表示方法在所有测试方法之后运行，而且该注解的使用限制与</span> <span>@BeforeAll</span> <span>一致</span></p></td></tr><tr><td><p id="u4e5238d3"><span>@Nested</span></p></td><td><p id="u192a88d5"><span>表示带注解的类是嵌套的非静态测试类，@BeforeAll 和 @AfterAll 方法不能直接在 @Nested 测试类中使用，除非修改测试实例生命周期</span></p></td></tr><tr><td><p id="ud02cd29d"><span>@Tag</span></p></td><td><p id="u24c80f12"><span>用于在类或方法级别声明用于过滤测试的标记</span></p></td></tr><tr><td><p id="ub11c55bb"><span>@Disabled</span></p></td><td><p id="u830bea66"><span>用于禁用测试类或测试方法</span></p></td></tr><tr><td><p id="u5e56bce6"><span>@ExtendWith</span></p></td><td><p id="ubcd9fe07"><span>用于注册自定义扩展，该注解可以继承</span></p></td></tr></tbody></table>


## JUnit 5 常用断言

^0b309d

下表提供了一些常用的 JUnit 5 断言方法。

<table id="yR1sf"><tbody><tr><td><p id="u98180bd6"><strong><span>断言</span></strong></p></td><td><p id="u4ca94c32"><strong><span>描述</span></strong></p></td></tr><tr><td><p id="u8f8d52b8"><span>assertAll</span></p></td><td><p id="u2366ccd5"><span>分组断言，执行其中包含的所有断言</span></p></td></tr><tr><td><p id="u317d2c9d"><span>assertEquals</span></p></td><td><p id="u771ddd8c"><span>判断断言预期值和实际值是否相等</span></p></td></tr><tr><td><p id="ub526c3c7"><span>assertNotEquals</span></p></td><td><p id="u060f8d1d"><span>判断断言预期值和实际值是否不相等</span></p></td></tr><tr><td><p id="u483c812a"><span>assertArrayEquals</span></p></td><td><p id="u422a1a2c"><span>判断断言预期数组和实际数组相等</span></p></td></tr><tr><td><p id="u32a3369b"><span>assertTrue</span></p></td><td><p id="u112df6f1"><span>判断断言条件是否为真</span></p></td></tr><tr><td><p id="u95391c18"><span>assertFalse</span></p></td><td><p id="ua7eaa6d8"><span>判断断言条件是否为假</span></p></td></tr><tr><td><p id="u7a8810af"><span>assertNull</span></p></td><td><p id="u8aa4baa8"><span>判断断言条件是否为空</span></p></td></tr><tr><td><p id="u98a679a7"><span>assertNotNull</span></p></td><td><p id="u92fcb9f2"><span>判断断言条件是否不为空</span></p></td></tr><tr><td><p id="u394f28b4"><span>assertSame</span></p></td><td><p id="u145050c2"><span>判断两个对象引用是否指向同一个对象</span></p></td></tr><tr><td><p id="u1c7992db"><span>assertTimeout</span></p></td><td><p id="uf7a9f67d"><span>断言超时</span></p></td></tr><tr><td><p id="ueccaf456"><span>fail</span></p></td><td><p id="u1cf879a1"><span>使单元测试失败</span></p></td></tr></tbody></table>





---
*citation*:: 
*reference*:: 
*relation*:: 