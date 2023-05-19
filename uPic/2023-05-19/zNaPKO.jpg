package com.netease.bclottery.core.enums;

import lombok.Getter;

/**
 * 通用 是否
 */
@Getter
public enum YesNoStatus {

    NO(0, "NO", "否"),
    YES(1, "YES", "是"),

    ;

    Integer code;
    String strCode;
    String remark;

    YesNoStatus(Integer code, String strCode, String remark) {
        this.code = code;
        this.strCode = strCode;
        this.remark = remark;
    }

    public static YesNoStatus get(String code) {
        for (YesNoStatus e : values()) {
            if (code.equalsIgnoreCase(e.getStrCode())) {
                return e;
            }
        }

        return null;
    }

    public static YesNoStatus get(Integer code) {
        for (YesNoStatus e : values()) {
            if (e.getCode().equals(code)) {
                return e;
            }
        }

        return null;
    }
}
