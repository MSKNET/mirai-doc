[mirai-core](../../index.md) / [net.mamoe.mirai.contact](../index.md) / [Member](index.md) / [unmute](./unmute.md)

# unmute

`abstract suspend fun unmute(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

解除禁言.

管理员可解除成员的禁言, 群主可解除管理员和群员的禁言.

### Exceptions

`PermissionDeniedException` - 无权限修改时抛出

**See Also**

[Member.isMuted](../is-muted.md)

[MemberUnmuteEvent](../../net.mamoe.mirai.event.events/-member-unmute-event/index.md)

