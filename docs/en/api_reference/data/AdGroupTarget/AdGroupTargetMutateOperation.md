# AdGroupTargetMutateOperation
AdGroupTargetMutateOperation object contains the targeting information for mutate/replace method.

### Service
+ [AdGroupTargetService](../../services/AdGroupTargetService.md)

### Namespace
[AdGroupTargetService#Namespace](../../services/AdGroupTargetService.md#namespace)

### Inheritance
+ Operation

<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
  <th>add</th>
  <th>set</th>
  <th>remove</th>
  <th>replace</th>
 </tr>
 <tr>
  <td>accountId</td>
  <td>xsd:long</td>
  <td>Account ID.</td>
  <td>Required</td>
  <td>Required</td>
  <td>Required</td>
  <td>Required</td>
 </tr>
 <tr>
  <td>operand[0..3000]</td>
  <td><a href="./AdGroupTarget.md">AdGroupTarget</a></td>
  <td>Targeting information for the target to be operated.</td>
  <td>Required</td>
  <td>Required</td>
  <td>Required</td>
  <td>Required</td>
 </tr>
 </table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
