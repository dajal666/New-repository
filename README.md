@ApiOperation(value = "用户信息", notes = "用户信息")
2
    @ApiImplicitParams({
3
                @ApiImplicitParam(name = "userId", value = "用户编号", required = false, dataType = "Integer"),
4
                @ApiImplicitParam(name = "userName", value = "用户名", required = false, dataType = "String"),
5
                @ApiImplicitParam(name = "status", value = "状态", required = false, dataType = "Integer"),
6
                @ApiImplicitParam(name = "createTime", value = "创建时间", required = false, dataType = "Date")
7
    }
8
    )
# New-repository
New repository
